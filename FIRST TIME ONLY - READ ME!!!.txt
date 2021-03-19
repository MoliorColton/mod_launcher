Welcome to the Client Extension! This is ESSENTIAL to playing the Molior RS mod, and MANY other servers.

This program acts as a client plug-in whose purpose is to improve the multi-player
experience of Neverwinter Nights 2.  It fixes several client crash bugs, and
adds some useful new features.


Quick Start & Overview
----------------------

The Client Extension can either plug-in to the player or DM client, or it can
operate as an independent DM client.  To get started with using the Client
Extension as a player or a DM, use one of the following methods:


(a) Start the game with the included NWLauncher program (recommended).

1)  Run NWLauncher.exe and the game will start with the client extension
    already active.  You need to keep NWLauncher.exe and ClientExtension.hdl
    in the same place for the launcher to work correctly.
    
    It is recommended that you use the game in windowed mode to get the most
    out of the client extension.
                
    You may pass command line arguments to the game by providing them to
    NWLauncher.exe, e.g. by creating a shortcut.  This is useful for launching
    the game in DM mode with the -dmc option.  You can also directly connect to
    a game server at startup by using the +connect <server> argument.  See the
    "Features" section for more details on how to create a shortcut to connect
    to a game server automatically.


2)  Log on to your server as normal and play the game.


                                    - or -


(b) Apply the client extension after starting the game.

1)  (First time only.)  Double-click hdlinstall.reg to install support for .hdl
     files.  You only need to perform this step once per computer.
     
2)  Start Neverwinter Nights 2 in normal or DM client mode, and go to the main
    menu.  It is recommended that you use Neverwinter Nights 2 in windowed mode
    but this is not strictly required.
     
3)  Navigate to where you have placed ClientExtension.hdl in Explorer,
    right-click the ClientExtension.hdl file, and choose the 'Apply' option
    from the menu that appears.
    
4)  Log on to your server as normal.  You must follow steps 3-5 again each time
    you exit Neverwinter Nights 2.  Be sure to apply the extension -before- you
    log on to your server.




  
Features
--------

The Client Extension includes a number of new features and bug fixes that are
designed to improve your multiplayer experience:

- A replacement for the Internet Server Browser functionality, formerly
  provided by GameSpy (official support has since been discontinued).  This
  enables players to locate other servers to join, as prior to the
  discontinuation of matchmaking services by GameSpy.

- An option to directly connect to a multiplayer game server from the command
  line.  Simply run NWLauncher.exe +connect <server> [+password <pw>] to start
  the game and directly connect to a server.  This can be used to create a
  shortcut to launch the game and connect to a particular server.  Here are
  some example command line:

  NWLauncher.exe +connect mynwn2pw.example.com
  NWLauncher.exe +connect mynwn2privatepw.example.com +password playerpassword
  NWLauncher.exe -dmc +connect mynwn2pw.example.com +password dmpassword

- Command history is now available for the client!  The client extension has a
  separate text-entry user interface which allows a history of all chat text
  that you send to be accessed.  Even text you enter in to the normal game chat
  interface is added to the command history, but you may only access the
  command history from the new text-entry user interface.  The new text-input
  user interface is described in the "Text-input User Interface" section.
  
- Larger chat messages can now be sent (up to approximately 4,096 characters).
  Please use this feature appropriately.  Long text messages do not cause any
  problems for normal clients or servers, but sending an overly long message
  may produce results that are difficult to read.  Large text messages are only
  available through the new text-input user interface.
  
 
Acknowledgements
----------------

Grinning Fool, for assistance with area decoding and portions of the game
object update message decoding.

Obsidian, for working to provide debug symbols for the Neverwinter Nights 2
client and server.  This has proven by far the most positive interaction with
a game developer that I've had to date, something that should be considered a
model for other game developers to emulate.

Brian Meyer, for bearing with several test builds and providing extensive
test work and valuable feedback.

Tero Kivinen <kivinen@iki.fi>, for decoding portions of the walkmesh on-disk
format.

KEMO, for bearing with me for extensive testing of DM cross-area creature
viewing and other assistance with debugging the server-side GUI scripts
involved.

tazpn, for releasing the source code to his Neverwinter Nights 2 model import
and export tool, from which information on the game's bone system was derived.

Numerous beta testers for providing feedback, catching issues, and suggesting
new features.
