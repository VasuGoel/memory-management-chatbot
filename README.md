# MemBot
Interactive ChatBot build using wxWidgets cross-platform GUI library and optimized with modern C++ memory management in mind. The ChatBot code creates a dialogue where users can ask questions about some aspects of memory management in C++. After the knowledge base of the chatbot has been loaded from a text file (which by the way you can add to), a knowledge graph representation is created in computer memory, where chatbot answers represent the graph nodes and user queries represent the graph edges. After a user query has been sent to the chatbot, the Levenshtein distance is used to identify the most probable answer.

Modern memory management techniques used are Dynamic Memory Allocation (The Heap), Resource Copying Policies with Copy and Move semantics using Lvalues and Rvalues for implementing the Rule of Five, Resource Acquisition Is Initialization (RAII), Smart Pointers and Transfering ownerships.

## Cloning
You can clone the repository with HTTPS:
```
https://github.com/VasuGoel/OpenStreetMap-route-planner.git
```
or with SSH:
```
git@github.com:VasuGoel/OpenStreetMap-route-planner.git
```

## Dependencies
* cmake >= 3.11
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)
* wxWidgets >= 3.0
  * Linux: `sudo apt-get install libwxgtk3.0-dev libwxgtk3.0-0v5-dbg`
  * Mac: There is a [homebrew installation available](https://formulae.brew.sh/formula/wxmac).
  * Installation instructions can be found [here](https://wiki.wxwidgets.org/Install).
  
## Compiling and Running
### Compiling
To compile the project, create a `build` directory and change to that directory:
```
mkdir build && cd build
```
From within the `build` directory, run `cmake` and `make` as follows:
```
cmake ..
make
```

### Running
The executable will be placed in the `build` directory. From within `build`, you can run the project as follows:
```
./membot
```
