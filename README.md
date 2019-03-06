# readmeTest
this is a read me test 


## Ruby Sass is Deprecated!

Ruby Sass is in a sunset period where only critical bugs and CSS compatibility
issues will be fixed. It will be completely unmaintained as of 26 March 2019.
See [`the Sass website` 123][] for details, and consider switching to the [`sassc`
gem][]

[`the Sass website` 123]: https://sass-lang.com/ruby-sass
[`sassc` gem]: https://rubygems.org/gems/sassc

# title 1

# title 2 

## Using

Sass can be used from the command line
or as part of a web framework.
The first step is to install the gem:

	gem install sass

After you convert some CSS to Sass, 
	
	you can run

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
