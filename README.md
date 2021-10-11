# m-center

Latest version of m-center release can be downloaded from [here](https://www.u-blox.com/en/product/m-center).
![image](https://user-images.githubusercontent.com/39135614/133438111-dc2cdd53-f5c5-4c0f-8d7d-6dfa5c0e9ac9.png)



## AT-Scripts Directory:
This directory contains the AT Scrips, these scripts can be used to send AT commands and get responses in a specific manner or on some event using if, else conditions, and loops.
GitHub AT_Scripts can be downloaded using the m-center GitHub download button.
![image](https://user-images.githubusercontent.com/39135614/132846109-7e1f4ef0-500a-422f-bd89-62a9c54899f5.png)


### How to use:
At the bottom of AT terminal window there is a panel from which it is possible to select an AT script from a drop down menu and run it.
The AT scripts are text files in which every line corresponds to one AT command.
It is also possible to define a global time-out in seconds.
For every AT command, m-center will wait for a response before moving to the next command.
Whenever a timer expires, the script will be aborted, and the remaining commands will not be sent to the modem.
The iteration of a script can be set in Loop Count.
The range is from "0" to "999999".
If the loop count value is set to "0", the selected AT script will run for an indefinite amount of time.
The iteration number is displayed in the "iteration" label.

### Create New AT Script:
The AT script files have ".atl" extension and are saved in "par\at_script" in the m-center folder.
To create a new AT script file, open a file in notepad and save it with extension ".atl" at location "m-center\par\at_script".
Add AT commands in small or capital letters and save it.
Make sure each AT command is entered in a separate line.

See m-center **help** menu for more details.

**Code formatting guidelines** to be applied:**[here](https://github.com/u-blox/m-center/wiki/AT-Scripting-Formatting-Guidelines)**
