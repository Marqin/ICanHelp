Build on GNU/Linux
==================

1. NuGet might be needed for missing libraries.
   If you experience problem "Error getting response stream":
   http://stackoverflow.com/questions/15181888/nuget-on-linux-error-getting-response-stream
   To install missing libraries:
   $ mono --runtime=v4.0 ~/Pobieranie/NuGet.exe restore 

2. You have install nodejs and then missing nodejs programs:
   grunt, grunt-cli and typescript
   
   You can do this GLOBALLY by:
   $ sudo npm install -g grunt grunt-cli typescript
   or LOCALLY:
   $ npm install grunt grunt-cli typescript
   where npm is nodejs packet manager.

3. To build simply run:
   xbuild
