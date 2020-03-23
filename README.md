# SocketServerWebREPL
Interactive Python Console over a WebSocket connection, allowing users to acces a Python REPL (read–eval–print loop) from any web browser, interacting with the Python interpreter in real time from anywhere. Part of BIPES Project - Block based Integrated Platform for Embedded Systems (http://www.bipes.net.br), which allows a block based program to be translated into Python code, and sent to a device that has a Python interpreter, such as a Raspberry Pi, BeagleBone or even a PC, to be executed quickly from the blocks.

Usage:

1. Download this Python Code: git clone https://github.com/rafaelaroca/SocketServerWebREPL.git
2. Run this program (cd SocketServerWebREPL; python socketserverWebREPL.py)
3. Access the Interactive Console and remotely run Python code or block program
4. Web client example: https://micropython.org/webrepl/#127.0.0.1:1338/ (replace 127.0.0.1:1338 with the correct port and IP)
5. BIPES client example: http://www.bipes.net.br/beta1/

== More info

This code is mainly on socketserverREPL and PyWSocket.

PyWSocket by Sanket 
https://superuser.blog/websocket-server-python/
https://tools.ietf.org/id/draft-ietf-hybi-thewebsocketprotocol-09.html
https://github.com/sanketplus/PyWSocket

Based also on socketserverREPL by Ivor Wanders
https://github.com/iwanders/socketserverREPL

WebSocket Protocol
https://tools.ietf.org/html/rfc6455

#Security Alert:
Use at your own risk! Opening a Python console to be accessed from any web browser is a security risk, depending on the device you are running  SocketServerWebREPL. Please, use it for development and test in controlled environments.

