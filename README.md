# How-to-create-booting-.adf-image-
This is a guide on how to build a booting .adf image
This one boot AMODS PROFESSIONAL COMPILED Programs
Load a empty .adf image 800kb
build a folder s make a startup-sequence file with DF0:PROGRAM text inside
make Libs folder with amos library
execute install df0: command


you need to type this in cli: 

"install df0:" 

This will make the disk bootable. 
Then you need to create a folder named "s" 
And a file named "startup-sequence" inside the s folder 
For that you can use the workbench tool "ed" . It just needs to be a simple text file with the name of the program to be booted in it. 

Of course you need to have all the libraries on the disk if they are needed and their location should be assigned as "libs" 

like: 

"assign libs: df0:libs"
