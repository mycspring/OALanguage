###OALanguage Compiler and Shell
编译原理的大作业---自定义强类型语言OALanguage  
目前做到显示语法树和token stream  

using lex & yacc  
gui using electron

usage
```
npm install
node-gyp configure
node-gyp build
node-gyp rebuild --target=0.34.1 --arch=x64 --dist-url=https://atom.io/download/atom-shell
npm start
```