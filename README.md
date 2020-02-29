# WebAssembly
My works related to WebAssembly.

## Table of Contents
1. [Introduction.](#introduction)
2. [Official references websites.](#references)
3. [GitHub notes.](#github)
4. [GitHub repository calculation.](#calculation)

<a name="introduction"></a>
## 1. Introduction.
<img src="webassembly.png" height="150"> 
WebAssembly (abbreviated Wasm) is a binary instruction format for a stack-based virtual machine. Wasm is designed as a portable target for compilation of high-level languages like C/C++/Rust, enabling deployment on the web for client and server applications. <br /><br />

The main goal of WebAssembly is to enable high-performance applications on web pages, but the format is designed to be executed and integrated in other environments as well. WebAssembly became a World Wide Web Consortium recommendation on 5 December 2019 and, alongside HTML, CSS, and JavaScript, it is the fourth language to run natively in browsers. 

In order to use Wasm in browsers, users may use Emscripten SDK to compile C++ (or any other LLVM-supported language such as D or Rust) source code into a binary file which runs in the same sandbox as regular JavaScript code. Emscripten provides bindings for several commonly used environment interfaces like WebGL; it has access only to an expandable memory and a small number of scalar values. There is no direct Document Object Model (DOM) access; however, it is possible to create proxy functions for this, for example through stdweb, web_sys, and js_sys when using Rust language.

The World Wide Web Consortium (W3C) maintains the standard with contributions from Mozilla, Microsoft, Google, and Apple.

<a name="references"></a>
## 2. Official references websites. 
WebAssembly official website : https://webassembly.org <br />
Emscripten official website : https://emscripten.org <br />

**_WebAssembly related technologies_** <br />
Express : https://expressjs.com <br />
WebAssembly by wasdk : https://wasdk.github.io/WasmFiddle <br />
WebGL : https://get.webgl.org <br />

**_WebAssembly documentation by Mozilla_** <br />
WebAssembly.instantiateStreaming() by Mozilla : https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WebAssembly/instantiateStreaming <br />
WebAssembly.Instance by Mozilla : https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WebAssembly/Instance <br />
WebAssembly.Module.exports() by Mozilla : https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/WebAssembly/Module/exports <br />

**_WebAssembly related articles_** <br />
Loading and running WebAssembly code by Mozilla : https://developer.mozilla.org/en-US/docs/WebAssembly/Loading_and_running <br />
Fast, parallel applications with WebAssembly SIMD by v8.dev : https://v8.dev/features/simd <br />
WebAssembly and SIMD by Nick Lewycky : https://medium.com/wasmer/webassembly-and-simd-13badb9bf1a8 <br />
Emscripting a C library to Wasm by Surma : https://developers.google.com/web/updates/2018/03/emscripting-a-c-library <br />
An Introduction to Web Assembly by Codelabs : https://codelabs.developers.google.com/codelabs/web-assembly-intro/ <br /> 

**_WebAssembly projects_** <br />
Qt on the web : https://www.qt.io/qt-examples-for-webassembly <br />
squoosh : https://squoosh.app/ <br />
WebAssembly proposals : https://github.com/webassembly/proposals <br />
WebAssembly Explorer : https://mbebenita.github.io/WasmExplorer/ <br />

**_WebAssembly developers_** <br />
Lin Clark : https://github.com/linclark, https://twitter.com/linclark <br />
Surma : https://github.com/surma, https://twitter.com/DasSurma, https://surma.dev <br />
Deepti Gandluri : https://github.com/dtig, https://twitter.com/dptig <br />

<a name="github"></a>
## 3. GitHub notes.
Clone the current GitHub remote repository contents into local machine.
```
$ git clone https://github.com/syakirharis25/WebAssembly.git
$ cd WebAssembly/
$ git remote -v
$ git status
```

<a name="calculation"></a>
## 4. GitHub repository calculation.
```
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Markdown                         1              7              0             25
-------------------------------------------------------------------------------
```
Refer to : https://github.com/syakirharis25/cloc
