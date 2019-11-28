# Pseudocoder Color Theme

Always a lil unsatisfied with the other color schemes I come across, so this is mine. 

Adapted from Dayle Rees' "Peacocks In Space (High Contrast)", and also using some code from their [color-themes repo](https://github.com/daylerees/colour-schemes) to generate themes for multiple editors.

![Python Example](/screenshots/pseudocoder_python.png)

I made this theme in PyCharm initially, and then adapted it into the description in /build/resources/themes/pseudocoder.json. I'm sure I missed some of the hyperdescriptive Jetbrains settings in doing so, but it gets the gist. The original .icls is included in pseudocoder/jetbrains_source.  Jetbrains and Sublime Text are the two editors that I've manually updated the build code for, ymmv with the others.

This theme was designed for Python, though through Dayle Rees' bindings many parts of other languages have basic highlighting. 

# Editing and Building

* To edit the components of the theme, edit the /build/resources/themes/pseudocoder.json file
* Themes for different editors are made from files in the /build/resources/patterns folder. Edit those to add new highlighting targets

To build the themes, 
* Enter the `build` directory
* Make sure [Composer](https://getcomposer.org/download/) is installed
* Install the dependencies: `php composer.phar install`
* Build the themes `php run.php raincolour`


