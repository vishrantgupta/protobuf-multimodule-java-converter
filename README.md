## Protobuf multi-module project code generation example

This repo is for generating Java class from `.proto` message. It supports `proto2` and `proto3`.

### Command:

`mvn clean install`

Please note the directory structure, where you have to place the proto files (you are create a subfolder):

<pre>
src
 |---- main
        |----- proto
   </pre>

Change following statement in `pom.xml`

`<protocExecutable>path_of_protoc.exe</protocExecutable>`

**Known:** improvement can be done for dependency management
