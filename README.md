# Lumify

![ScreenShot](web/src/main/webapp/img/lumify-logo.png?raw=true)

Lumify is an open source big data analytical tool and knowledge discovery. See the [project page] (http://lumify.io) for more details. Basically, it's a way to aggregate your data and extract useful insights.

## Getting Started

Lumify supplies a pre-built virtual machine, however if you would like to build the project from source please see the corresponding section below.

[Pre-built VM Instructions] (docs/PREBUILT_VM.md)

[Build from source Instructions] (docs/BUILD_FROM_SOURCE.md)

## Disclaimers
* The following Titan properties are required on every vertex:
    * ```title```
    * ```_subType```: concept id
    * ```type```: type of concept (i.e. Look at VertexType.java)
* Accumulo must have a row structure with a SHA256 hash for the row key.

## License

Copyright 2013 Altamira Technologies Corporation

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

