# Textmate 960gs Bundle

This is a pretty simple bundle that lets you create websites using 960gs in a snap. The goal is to minimize the time you spend writing grid-specific code and maximize the time you spend creating awesome websites and experiences using 960gs. For more information on this bundle and the motivation behind it, [click here](http://helloform.com/blog/2010/05/960gs-textmate-bundle/).

![Screenshot](http://helloform.com/p/960/images/960gsbundle.jpg)

## Installing

	cd Library/Application\ Support/TextMate/Bundles/
	git clone git://github.com/fredoliveira/textmate-960gs.git 960gs.tmbundle

You may need to reload your bundles on Textmate for the change to take effect. Or just restart the application.

## Snippet examples

The bundle includes a few snippets that get you started with using 960gs to write grid-based pages.

### `c12` and `c16` - Grid Containers

Lets say you want to include a 12-column container. You can do it by simply writing:

	c12

Which expands to:

	<div class="container_12" id="name">
		(cursor will be here)
	</div>

Similarly, you can use `c16` to generate a 16-column container.

### `gg` - Grid elements

You can use snippets such as `g1`, `g2`, `g4`, `g8`, `g12` or a more flexible `gg` to expand into elements with a given number of columns. As an example, if you write,

	g4

You'll get:

	<div class="grid_4">
		(cursor will be here)
	</div>

### `pp` - Pre-packaged grids

There are also a couple of pre-packaged grids for common uses. Use `pp` to access a menu choice for these. Examples are below:

#### 3 column grid inside a 12 column container

	<div class="container_12" id="name">
		<div class="grid_4">
			column one
		</div>
		<div class="grid_4">
			column two
		</div>
		<div class="grid_4">
			column three
		</div>
	</div>

#### 4 column grid inside a 12 column container

	<div class="container_12">
		<div class="grid_3">
			column one
		</div>
		<div class="grid_3">
			column two
		</div>
		<div class="grid_3">
			column three
		</div>
		<div class="grid_3">
			column four
		</div>
	</div>


## Author information

Fred Oliveira
http://helloform.com
http://twitter.com/f
