#Remove string 1.0
by Pedro Parracho <pedro.parracho@gmail.com>

## Description:
Automator workflows to remove a	fixed string for the filename of a bunch of files
 
## Install
To install you need to copy the workflows to the folder `~/Library/Services`.

##Feature
Given the string `removeThis`, it will find and remote it from the filename of selected files:  
`file_1_removeThis.txt` -> `file_1_.txt`  
`file_2_removeThis.txt` -> `file_3_.txt`  
`file_removeThis_3.txt` -> `file__3.txt`  
## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc/3.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/3.0/">Creative Commons Attribution-NonCommercial 3.0 Unported License</a>.