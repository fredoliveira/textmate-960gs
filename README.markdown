# Textmate 960gs Bundle

This is a pretty simple bundle that lets you create websites using 960gs in a snap. The goal is to minimize the time you spend writing grid-specific code and maximize the time you spend creating awesome websites and experiences using 960gs. 

## Installing

	cd Library/Application\ Support/TextMate/Bundles/
	git clone git://github.com/fredoliveira/textmate-960gs.git 960gs.tmbundle

You may need to reload your bundles on Textmate for the change to take effect. Or just restart the application.

## Snippet examples

The bundle includes a few snippets that get you started with using 960gs to write grid-based pages. 

### Containers

Lets say you want to include a 12-column container. You can do it by simply writing:

	c12 (press tab)

Which expands to:

	<div class="container_12" id="name">
		(cursor will be here)	
	</div>

Similarly, you can use `c16` to generate a 16-column container.

### Grid elements

You can use snippets such as `g1`, `g2`, `g4`, `g8`, `g12` or a more flexible `gg` to expand into elements with a given number of columns. As an example, if you write,

	g4 (press tab)

You'll get:

	<div class="grid_4">
		(cursor will be here)
	</div>

## More coming soon 

Keep an eye on this space.