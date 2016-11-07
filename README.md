# RPNCalc
RPN Calculator plugin for Pythonista on iOS

This is an RPN calculator that runs using Pythonista, a Python
environment for iOS available on the AppStore. Load this script and
the pyui file into a folder and run the .py script. You can also add
a shortcut to your home window using the Pythonista way of doing so.

Some features that this calculator can do:
    > 20 number stack, can be easily changed by adopting the length
      of the global value, i.e., global stack = numpy.zeros(20)
    > The second layer of commands can be reached by the button 
      2nd on the left side
    > Your string formatting on the display can be changed by pressing
      the button std (standard formatting) on the left. There are 
      various options, have a look on what you like best or change
      it (subroutine button_formatting)
    > Switch easily from radians to degrees by the click of a button
      rad -> deg -> rad. Whatever you like.
    > Every number that is displayed can be copied into the clipboard
      using the copy button on the left of the screen.
    > You can either swap x and y with the button, or you can bring
      any number in on the display to the x location by clicking
      on it.
    > Reset: Secondary function on the 'Zero' button, resets the whole
      stack to np.zeros()

Please drop me a line if you find any Problems with this program. 
Currently not all errors are cought within the software. Please
also let me know if you have any wishes / anything you would like 
me to add.

Currently on my ToDo list:
    > Store variables with STO and recall them with RCL
    > Write the stack to a file whenever you change it (barebones
      are already coded but not yet used) and load it again when 
      you start the calculator back up
    > Store and reload your stored variables.
    > Store your preferred settings and load them again. right now
      the calculator starts with my preferred settings
