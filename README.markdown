# Textmate 960gs Bundle #

This is a pretty simple bundle that lets you create websites using 960gs in a snap. The goal is to minimize the time you spend writing grid-specific code and maximize the time you spend creating awesome websites and experiences using 960gs. 

## Installing ##

<pre>
cd Library/Application\ Support/TextMate/Bundles/
git clone git://github.com/fredoliveira/textmate-960gs.git 960gs.tmbundle
</pre>

You may need to reload your bundles on Textmate for the change to take effect. Or just restart the application.

## Snippet examples ##

The bundle includes a few snippets that get you started with using 960gs to write grid-based pages. 

### Containers ###

Lets say you want to include a 12-column container. You can do it by simply writing:

<pre>
c12 (press tab)
</pre>

Which expands to:

<pre><code>
<div class="container_12" id="name">
	(cursor will be here)	
</div>
</code></pre>

Similarly, you can use <pre>c16</pre> to generate a 16-column container.

### Grid elements ###

You can use snippets such as <pre>g1</pre>, <pre>g2</pre>, <pre>g4</pre>, <pre>g8</pre>, <pre>g12</pre> or a more flexible <pre>gg</pre> to expand into elements with a given number of columns. As an example, if you write,

<pre>
g4 (press tab)
</pre>

You'll get:

<pre><code>
<div class="grid_4">

</div>
</code></pre>

## More coming soon ##

Keep an eye on this space.