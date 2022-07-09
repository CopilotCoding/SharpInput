## InputSharp
This source file contains windows API virtual key codes and mouse event flags converted from C to C#, as well as some platform invokes.

This is useful as a replacement for manually writing out every virtual key code you need to use in your program.

Instead you can add this source code to your project to access the Windows API input from user32.dll.

I made sure to keep all the original comments from microsoft in place, as well as to include every single mouse and keyboard input code.

If you do not know what this is or how to use it I suggest that you read the source and documentation:

# Virtual key codes:
https://docs.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes

# Mouse events:
https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-mouse_event
# .NET Platform invoke wiki:
https://pinvoke.net/
# Win32 API:
https://docs.microsoft.com/en-us/windows/win32/
