# Oldentide

#####A Game Where You Can Be Anyone.

==================================

####Project Information:

**Project name**: Oldentide<br>
**Initial Starting Date**: 2/9/2013<br>
**Principal Author**: Joseph DeVictoria<br>
**Contributing Authors**: Scott Heidbrink<br>
**Platform**: Unreal Engine 4<br>
**Languages**: C++, C, SQLite3, (Python)<br>
**Project Website**: [www.oldentide.com](http://www.oldentide.com)<br>
**Wiki**: [Github Wiki](https://github.com/Oldentide/Oldentide/wiki)<br>
**Tasks**: [Gihub Wiki Task List](https://github.com/Oldentide/Oldentide/wiki/Tasks)<br>
**Contact**: jldevictoria@gmail.com

==================================

####Directories:

**Artifacts**: A place where any previous iteration of code goes.<br>
**Concepts**:  A place where any concept art, drawings, sketches or purely conceptual code goes.<br>
**Config**:    Configuration settings for Unreal Engine Editor.<br>
**Content**:   Where Unreal Assets are stored once imported into the engine.<br>
**Partial**:   A place where any intermediate asset work goes.<br>
**Raw**:       An intermediate asset storage layer for Unreal Engine.<br>
**Server**:    A place where dedicated server code goes. (Complimentary to Unreal game Code.)<br>
**Source**:    This is where Unreal Engine game source is stored.  (Complimentary to Server Code.)<br>

###Please contact me immediately if you see any bugs or want to contribute.  I need help developing the game!



==================================

###How to run the Oldentide server:

In linux, cd into Server/ and run the make command.
In order for the server to properly build, you will need to make sure that these packages are installed:

    sqlite3
    libsqlite3-dev

If everything built properly, run

    cd bin/
    ./Server 1337

where 1337 is the port the server is using.

To test that the server is running, in a separate terminal, run

    ./Client 127.0.0.1 1337

or

    ./Client localhost 1337

where 127.0.0.1 is the address of the server (localhost) and 1337 is the port of the server.
