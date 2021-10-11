
## Common Library ##
**common_lib** directory can be used if some reusable functions needs to be maintained separately for multiple scripts.

This directory should be placed in root path of scripting directory.

E.g.,

![image](https://user-images.githubusercontent.com/39135614/132848381-6a7fb581-49b5-44e7-8fd9-dbb707fc0f1f.png)	   
All the scripts in the *at_scripts* directory and *sub-directories* can use common library functions.
There is no need to include them explicitly in each script.
m-center scripting will include all functions from common_lib directory automatically.

## Rules ##
These syntax rules need to be followed for lib compatibility.

- **COMMENTS:** **\\\\** shall be used for comments in the string. Avoid using **#** for comments in lib directory.

- **PAUSE:**	PAUSE(ms);

- **ECHO:**  	ECHO("Hello World");

- **SENDAT:** Use SENDAT("AT",1000,"OK") macro to send AT command. Using AT command directly without macro will not work.
