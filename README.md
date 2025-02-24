# drill-docker

[![license](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

[drill](https://github.com/fcsonline/drill) (http load tester) docker image based on Alpine Linux.


## Usage in OCP
```bash
oc apply -f benchmarkcm.yml
oc apply -f job.yml
```




## Usage
```bash
docker run xridge/drill --help
```

## Build details
OpenSSL is built in the image using musl-gcc so that drill (and hyper) can
successfully built into a static image.

## License
Copyright (c) 2019 [xridge.io](https://xridge.io)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
