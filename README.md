# Derrick
[![PIP release](https://img.shields.io/badge/pypi-v0.0.1-yellow.svg)](https://github.com/alibaba/derrick)
[![Platform](https://img.shields.io/badge/platform-Windows&Linux&Mac-green.svg)](https://github.com/alibaba/derrick)
[![Language](https://img.shields.io/badge/language-NodeJs&Java&Python-red.svg)](https://github.com/alibaba/derrick)
[![GitHub release](https://img.shields.io/badge/release-0.0.1-green.svg)](https://github.com/alibaba/derrick/releases)
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)


Derrick is a tool to help you dockerizing application in seconds. Derrick focus on the developer's workflow in local development environment. Derrick will inspect your workspace and generate Dockerfile, docker-compose.yml, Jenkinsfile, etc. for you. You can simply use Derrick to stream line your DevOps process in container way smoothly.

<img src="http://container-service.oss-cn-beijing.aliyuncs.com/derrick.png" width=100%/>    

Using Derrick is very simple:    
1. `derrick init` to dockerize your application based on Derrick.    
2. `derrick build` to build your application to a Docker image.          
3. Use your favorite text editor to modify the Dockerfile or some others and run your application in local.        
4. Integrate into your workflow and have fun.       


## Documentation
* <a href="https://github.com/alibaba/derrick/wiki">Documentation Home</a>
* <a href="https://github.com/alibaba/derrick/wiki">Frequently Asked Questions</a>  

## Installation

```
pip install alibaba-derrick
```

### *License*
This software is released under the Apache 2.0 license.
