![ublox-logo](https://user-images.githubusercontent.com/6113690/137148466-077df768-7cd3-436a-91a6-29e354ee60ea.png)

# m-center

The latest version of m-center release can be downloaded from [here](https://www.u-blox.com/en/product/m-center).

Visit the [Wiki page](https://github.com/u-blox/m-center/wiki) for further instuctions and details on the scripts use.

![m-center_Main_01](https://user-images.githubusercontent.com/6113690/194055231-b26950f1-14fb-48bf-b230-da8ef966e819.png)



## AT-Scripts Directory:
This directory contains the AT scripts, these scripts can be used to send AT commands and get responses in a specific manner or on some event using if, else conditions, and loops.
GitHub AT scripts repository can be automatically downloaded using the m-center GitHub download button.

![m-center_Scripts](https://user-images.githubusercontent.com/6113690/194054993-eb0ca850-e601-4be7-a2d2-e736b3194e36.png)


### How to use:
At the bottom of AT terminal window, there is a panel from which it is possible to select an AT script from a drop-down menu and run it.
The AT scripts are text files in which every line corresponds to one AT command.
It is also possible to define a global time-out in seconds.
For every AT command, m-center will wait for a response before moving to the next command.
The iteration of a script can be set in 'Loop Count'.
The range is from "0" to "999999".
If the loop count value is set to "0", the selected AT script will run for an indefinite amount of time.
The iteration number is displayed in the 'Iteration' label.

### Create New AT Script:
The AT script files are simple text file with the `.atl` extension.
The user can create a new AT script by creating a file on notepad, or any other text editor application, and saving it with the `.atl` extension.
Scrips accept AT commands in small or capital letters, the only constraint is to write each AT command in a separate line.

See m-center **help** menu for more details.

**Code formatting guidelines** to be applied can be found  **[here](https://github.com/u-blox/m-center/wiki/AT-Scripting-Formatting-Guidelines)**.