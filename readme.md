## vscode extension ##

  **vscode-proto3**

  **protolint**

  - `brew tap yoheimuta/protolint `
  
  - `brew install protolint`


## Install ## 

brew install protobuf 


## Command ##

__For JS plugin__

  1. Download the file `https://github.com/protocolbuffers/protobuf-javascript/releases` and choose your version
  
  - `protobuf-javascript-3.21.2-osx-aarch_64.zip` For Mac ARM chip

  - `protobuf-javascript-3.21.2-osx-x86_64.zip` For Mac Intel chip

  - `protobuf-javascript-3.21.2-win64.zip` For Windows

  - `protobuf-javascript-3.21.2-linux-x86_64.zip` For Linux

  2. Copying `bin/protoc-gen-js` into the same directory as `protoc` Which often locate at `/user/local/bin/protoc` or `/user/bin/protoc`. On Mac OS X, it would be `/opt/homebrew/Cellar/protobuf/21.12/bin`for example

  &nbsp;&nbsp;&nbsp;&nbsp;____Or just install lower version____

  - `brew install protobuf@3`

  - `brew link --overwrite protobuf@3`

__For Golang plugin__

  1. Install in terminal `go install google.golang.org/protobuf/cmd/protoc-gen-go@latest`
  
__Execute the command__
  1. With normal language: JavaScript, Java, Python, C#, C++ ... use this command
  
  - `protoc --cpp_out=. *.proto`

  - `protoc --java_out=java --python_out=python --js_out=javascript proto/simple.proto`

  2. With golang use step below

  - create new folder

  - create module with `go mod init example.com/m`

  - 
