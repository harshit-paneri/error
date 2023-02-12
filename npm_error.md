```
D:\GSOC\repos\Webiu>npm install
npm WARN deprecated core-js@2.6.12: core-js@<3.23.3 is no longer maintained and not recommended for usage due to the number of issues. Because of the V8 engine whims, feature detection in old core-js versions could cause a slowdown up to 100x even if nothing is polyfilled. Some versions have web compatibility issues. Please, upgrade your dependencies to the actual version of 
core-js.
npm WARN cleanup Failed to remove some directories [
npm WARN cleanup   [
npm WARN cleanup     'D:\\GSOC\\repos\\Webiu\\node_modules',
npm WARN cleanup     [Error: EPERM: operation not permitted, rmdir 'D:\GSOC\repos\Webiu\node_modules\gatsby-recipes\src\providers\gatsby\fixtures'] {
npm WARN cleanup       errno: -4048,
npm WARN cleanup       code: 'EPERM',
npm WARN cleanup       syscall: 'rmdir',
npm WARN cleanup       path: 'D:\\GSOC\\repos\\Webiu\\node_modules\\gatsby-recipes\\src\\providers\\gatsby\\fixtures'
npm WARN cleanup     }
npm WARN cleanup   ]
npm WARN cleanup ]
npm ERR! code 1
npm ERR! path D:\GSOC\repos\Webiu\node_modules\node-sass
npm ERR! command failed
npm ERR! command C:\Windows\system32\cmd.exe /d /s /c node-gyp rebuild
npm ERR! gyp info it worked if it ends with ok
npm ERR! gyp info using node-gyp@3.8.0
npm ERR! gyp info using node@14.18.0 | win32 | x64
npm ERR! gyp ERR! configure error
npm ERR! gyp ERR! stack Error: Command failed: D:\installed\py6\python.EXE -c import sys; print "%s.%s.%s" % sys.version_info[:3];
npm ERR! gyp ERR! stack   File "<string>", line 1
npm ERR! gyp ERR! stack     import sys; print "%s.%s.%s" % sys.version_info[:3];
npm ERR! gyp ERR! stack                                ^
npm ERR! gyp ERR! stack SyntaxError: invalid syntax
npm ERR! gyp ERR! stack
npm ERR! gyp ERR! stack     at ChildProcess.exithandler (child_process.js:383:12)
npm ERR! gyp ERR! stack     at ChildProcess.emit (events.js:400:28)
npm ERR! gyp ERR! stack     at maybeClose (internal/child_process.js:1058:16)
npm ERR! gyp ERR! stack     at Process.ChildProcess._handle.onexit (internal/child_process.js:293:5)
npm ERR! gyp ERR! System Windows_NT 10.0.19044
npm ERR! gyp ERR! command "C:\\Program Files\\nodejs\\node.exe" "D:\\GSOC\\repos\\Webiu\\node_modules\\node-gyp\\bin\\node-gyp.js" "rebuild"
npm ERR! gyp ERR! cwd D:\GSOC\repos\Webiu\node_modules\node-sass
npm ERR! gyp ERR! node -v v14.18.0
npm ERR! gyp ERR! node-gyp -v v3.8.0
npm ERR! gyp ERR! not ok

npm ERR! A complete log of this run can be found in:
npm ERR!     C:\Users\Harshit Paneri\AppData\Local\npm-cache\_logs\2023-02-12T08_47_44_524Z-debug-0.log
```
