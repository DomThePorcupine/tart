This is a simple, and fairly useless wrapper tool for tar. I got tired of 
always typing a bunch of switches, and felt it would be easier without them since I 
basically only use tar to extract files.

WARNING tart defaults to removing the tar.* file after it is extracted!!!!

------------------------------------------------------
-------------------------USAGE------------------------
------------------------------------------------------
Here is how it works:

What you type with tar:

tar -zx(v)f myfile.tar.gz

tar -x(v)f myfile.tar.xz

tar -jx(v)f myfile.tar.bz2

becomes

tart myfile.tar.xz/gz/bz2

------------------------------------------------------
---------------------INSTALLATION---------------------
------------------------------------------------------
To install this tool copy it to a folder in your path,
and then make it executable

Use this to tell you your path directories
echo $PATH
Choose one of the above directories and use cp
sudo cp tart /usr/bin
Make it an executable file
sudo chmod +x /usr/bin/tart

Yay now you have tart and can be lazy like me :)

Suggestions to **porcupinebot@gmail.com** please!
