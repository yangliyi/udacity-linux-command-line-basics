# L3 Linux Filesystem
## The Working Directory
* pwd - Print working directory
* cd 
  * . - current directory 
  * .. - the parent of the current directory
  * directory_name - the directory in current directory
  * /direct/another_direct - full path of a directory 
  * can use either absolute path or relative paths
  
## Moving and Copying Files
* mv, cp 
  * source destination
  * item1 item2 item3 .. directory
  
## Making and Removing Directories
* mkdir - Making new directory
* rmdir - remove an existing directory
* rm -r directory_name - Remove directory with files or directories inside

## Globbing
* ls 
  * *html:
  	* app.html, new.html
  * app\*:
  	* app.js, app.css 
  * \*pp\*:
  	* app.js, bpp.html
  * b\*png:
  	* bear.png, box.png
  * app.{css,html}:
  	* app.css, app.html
  * bea?.png:
  	* bear.png, bean.png
  * be??.png:
  	* bees.png, beer.png
  * be[aeiou]r.png:
  	* bear.png, beer.png 
 
 