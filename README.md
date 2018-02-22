# AirBnB Clone Project

This project is the beginning of a full clone of the AirBnB web application. The first step of the process is to build a command interpreter with some basic class definitions and file storage.

## Getting Started
In order to get the AirBnB clone up and running the Github repository must first be cloned to your local machine with the following command:

### With SSH
```$ git clone git@github.com:jagrvargen/AirBnB_clone.git```

### With a URL
```$ git clone https://github.com/jagrvargen/AirBnB_clone.git```

Once downloaded, change into the AirBnB directory and open the console by typing:
```$ ./console.py```

## Features
This part of the project feautures a command line interpreter intended for future debugging. It includes a short list of commands intended to aid in creating and modifying user data stored in a JSON file.

### Command Interpreter

The command interpreter can be run in interactive mode via the following command:
```$ ./console.py```

The command interpreter can also be used in non-interactive mode by passing commands to it via piping:
```$ echo "help" | ./console.py```

#### Commands

Commands | Description | Usage
-------- | ----------- | -----
**quit** | Exit the console | **quit**
**EOF** | Exit the console | **C^d**
**help** | Open a help menu | **help** or **?**
**create** | Create a new instance of an object | **create** \<class_name\>
**show** | Prints the string representation of an instance | **show** \<class_name id\> or **<class name>.show(<id>)**
**destroy** | Deletes an object instance | **destroy** \<class_name id\> or **<class name>.destroy(<id>)**
**all** | Prints the string representation of all instances based on the class name, or all object instances in isolation. | **all** or **all** \<class_name\>
**update** | Update an object instance's attribute or value by name. | **update** \<class_name id attribute_name attribute_value\> or **<class name>.update(<id>, <attribute name>, <attribute value>)**
**count** | Returns an integer count of object instances | **<class name>.count()**

## Tests

This package contains extensive unittests to ensure sound functionality of all enclosed modules. Tests can be run via the command:
```$ python3 -m unittest discover tests```

## Bugs

No known bugs at this time.
