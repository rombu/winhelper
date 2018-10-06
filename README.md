# winhelper

# methods
GetWindowsList - return list windows on system. can do filtering windows by ProcessName, WindowTitle, WindowClass
GetWindowInfo - return window info by handle. processName, windowTitle, windowClass, width, height, left, top, isWindow, isWindowVisible, isIconic
GetWindowActive - return handle of active window
SetWindowActive - set on os active window by handle
GetWindowScreen - return screenshot window by handle format png, base64