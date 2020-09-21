# Desafio_2 Python

It was requested to write a code to control the turtlesim from Ros setting its destination position and accepted error

## Installation

Clone the repository and make sure you have the Ros environment 


## Usage
Open three terminals and runs the following command in this order:

First terminal in any directory -
```bash
roscore
```

Second terminal in any directory

```bash 
rosrun turtlesim turtlesim_node
```
Third terminal in the repository src directory:
```bash
./gotogoal.py
```
When running the third command the terminal will request you to set the X and Y position and finally the error scale permitted, than just press enter and the turtle in turtlesim will movie to the requested position

Note that if you want to request another position you have to press Ctrl+Z to end the current process and run the third command again
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
