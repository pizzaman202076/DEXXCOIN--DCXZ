# DEXXCOIN--DCXZ
4/18/21 - 0.0.2 update
  - new wallet layout
  - working on linux and mac compatibility atm
  - bug fixes
4/19/21
  - mining guide
  -Open File Explorer and go to your downloads directory.

Extract the zip file dexxcoin-qt-windows.zip

Open "Run" with the keyboard shortcut winkey + r.

Enter the following text behind "Open": notepad

Press on the button "OK".

Paste the following into notepad.

rpcuser=rpc_dexxcoin
rpcpassword=dR2oBQ3K1zYMZQtJFZeAerhWxaJ5Lqeq9J2
rpcallowip=127.0.0.1
listen=1
server=1
addnode=node1.walletbuilders.com

Click on the menu item "File" -> "Save As...".

The open dialog box will appear, click on "Save as type" and select the option "All Files (*.*)".

Enter the following text behind "File name": dexxcoin.conf

Click on the menu bar, type the following text %appdata% and press on the enter key. enter

Create the folder DexxCoin and open the folder.

Press on the button "Save".

Create a new file with the keyboard shortcut ctrl + n.

Paste the following into notepad.

@echo off
set SCRIPT_PATH=%cd%
cd %SCRIPT_PATH%
echo Press [CTRL+C] to stop mining.
:begin
 dexxcoin-cli.exe generate 1
goto begin

Click on the menu item "File" -> "Save As...".

The open dialog box will appear, click on "Save as type" and select the option "All Files (*.*)".

Enter the following text behind "File name": mine.bat

Click on the menu bar, open the location where you extracted the zip file dexxcoin-qt-windows.zip.

Press on the button "Save".

Open your wallet and execute mine.bat to mine your first block.
