# O2Server Emulator

Simple emulator program for the O2Jam client. Open source implementation of the O2EMU server.
Does not need visual basic to run. 

## Build
Requires boost::asio library to build. Open and build in Visual Studio.
On linux, run make in the O2ServerEmu directory. 

## Usage
- Grab a copy of the O2jam client
- Move the emu binary into the folder where it can see the Spt folder.
- Run the .bat file, which will start server and client.
- Emulator looks for and runs the following files
  - Channel1.spt
  - D007.spt
  - D270.spt
  - MusicList.spt
