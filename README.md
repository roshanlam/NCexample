# NCexample

# Pre setup
To start the work, install the following software on your computer:

* Node JS
* Npm

# Step 1
To initialize a new Npm directory, execute the command code: `npm init`. You will have to answer several questions to set the project. Finally, the `package.json` file that contains the basic information about the project will be created in the project directory. The list of necessary packages will be also stored in this file.

# Step 2
After you have set up the project, install the necessary packages. In this project you need only one package - “node-gyp”. It’s a tool that compiles Node.js addons.

Simply speaking, node-gyp compiles C/C++ for using it with Node.js. This package is compulsory for a lot of apps, as in many cases code that should be compiled is loaded along with the package.

One more peculiarity of node-gyp is that it compiles the code regardless of the operating system. This feature allows avoiding a number of mistakes related to the differences in operating systems for Node-based projects.

To set up node-gyp, execute the command `npm install g node-gyp`.

# Step 3
After you have installed the package for C/C++ code compilation, configure node-gyp within the project. First, create binding.gyp file inside the project. This file will contain information about node-gyp functioning.

# Step 4
Write and compile addon code

file: addon.cpp

