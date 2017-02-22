# ifcatwebsite
A simple website for the IFCAT foundation.


Made with Jekyll... because... why not :)

Installation to a webserver
---------------------------
Move the visible files from the output directory to the root of the webserver.


Editing and testdriving your edits
----------------------
You'll need jekyll to convert your pages/posts into nice looking HTML. 

Installation can be found here: https://jekyllrb.com/docs/installation/

This site uses the default jekyll theme, because we've got other things to do. :)


If you are in the parent directory, just run this:
<code>jekyll build --source input/ --destination output/</code>

Quirks
------
Jekyll doesn't seem to understand relative paths for assets. Be aware when editing the site. You can change the path to the assets in the _config.yml file in the input folder.
