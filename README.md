LocalFileServer
===============

Silly local C# server so we can edit local files .. works with windows and linux. 
To compile on linux, you need mono 2.xx. Then do dmcs LocalFileServer.cs

This gives a simple api to get read/write access to files on the folder its run on,
 or on a directory you supply it with. It doesn't do subfolders or anything more fancy.

usage:

[mono] LocalFileServer.exe [path_to_share] [port]