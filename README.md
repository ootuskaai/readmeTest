# Read me Example
The is a read me example.

# H1 title have 1 "#" sign
This is a way to make a h1~h6 tag.

h1 have 1 "#"sign

h2 have 2 "##" sign 

and so on....


# Make text link way..

This is a example about readme link.
We have 2 ways can make links.

Way 1:
Make link in one line.

Use the \[ and \] sign cover the link text .

\[ put the link text in here \] 

Then use \( and \) sign cover the link's url

It looks like \[ put the link text in here \]\(url here \). 

You can see the link below the link go to google search.

[put the link text in here ](https://www.google.com/).

Way 2:
Make link in separate line. (look like PS).

Use the \[ and \] sign cover the link text .

\[put the link text here way 2\].

Then alternate it in different line.

And use \: sign after the link text.

It look like this: \[put the link text here way 2\]\:url here .

You can see the link below the link go to google search.

[put the link text here way 2]

[put the link text here way 2]:https://www.google.com/


# Make em tag

In this example here we will show how to make am `em tag` here
now u can see the content "em tag" have a gary background..

Way 1: 
You need to use "\`"sign to cover you want to have content..

Way 2:
And this em tag can use in the link content
['This is a link jave gray background'](https://www.google.com/).


## Using

Sass can be used from the command line
or as part of a web framework.
The first step is to install the gem:

	gem install sass

After you convert some CSS to Sass, 
	
	you can run


You can even give them arguments

Even more powerful than variables,
mixins allow you to re-use whole chunks of CSS,
properties or selectors.
You can even give them arguments. 

```css
@mixin table-scaffolding {
  th {
    text-align: center;
    font-weight: bold;
  }
  td, th { padding: 2px; }
}

@mixin left($dist) {
  float: left;
  margin-left: $dist;
}

#data {
  @include left(10px);
  @include table-scaffolding;
}
```
