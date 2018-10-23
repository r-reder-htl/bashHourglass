# bashHourglass
This project delivers an easy way to add an hourglass to a bash script.
So when you write an own script where a certain job needs a long time you can call this terminal hourglass which 
will show the user that the job is ongoing.
When the time consuming job is done you can stop the hourglass.
## Installation
Just put the script "hourglass.sh" into to folder where you have your scripts.
If you want to use it on different places on your system you can add it to a PATH-environment location.
## Starting the hourglass
Within your script you have to call 
'''bash
hourglass.sh start
'''
If your copy of hourglass.sh is not in a PATH-environment you have to add a path to the call (see the example.sh script for details.)
## Stopping the hourglass
Within your script you have to place 
'''shell
hourglass.sh stop
'''
Consider the same strategie with the path as on starting the hourglass.
