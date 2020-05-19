# Arcade CASA Container
## Building a CASA container
1. cd into the relevant folder with the build file or create a new folder if necessary
2. execute 'make'
### Testing a Container
You will need to run the container in a graphical environment, such as arcade, to test the visual components of the CASA containers.

The following steps can be performed in a graphical container environment (such as arcade) to test that the container was built correctly.
1. Type the id command and ensure that user name is displayed.
2. Type 
```
source /opt/admit/admint_start.sh
admit
```
   and ensure that information on ADMIT is displayed
3. Run the ```casa``` command and ensure that the logging window opens.
4. Within CASA, type ```import admit``` and ensure that there is no error.
5. Exit CASA. Run the ```casaviewer``` command and ensure that casaviewing windows are displayed.
6. Exit ```casaviewer``` and exit the xterm.