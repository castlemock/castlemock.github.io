<center><h1>Castle Mock</h1></center>
<center><h2>Mock REST APIs and SOAP web-services</h2></center>

<p align="center">
    <a href="https://app.travis-ci.com/github/castlemock/castlemock"><img src="https://app.travis-ci.com/castlemock/castlemock.svg?branch=master"></a>    <a href="https://github.com/castlemock/castlemock/releases"><img src="https://img.shields.io/github/release/castlemock/castlemock.svg"></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/license-Apache%202-blue.svg"></a>
    <img src="https://img.shields.io/badge/platforms-Linux%C2%A0%7C%C2%A0macOS%20%7C%20Windows-blue">
    <a href="https://hub.docker.com/r/castlemock/castlemock/"><img src="https://img.shields.io/docker/pulls/castlemock/castlemock.svg"></a>
</p>

<p align="center">
<a class="github-button" href="https://github.com/castlemock/castlemock" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star castlemock/castlemock on GitHub">Star</a>

</p>

----

**Castle Mock** is a web application that provides the functionality to mock out RESTful APIs and SOAP web-services. This functionality allows client-side developers to completely mimic a server side behavior and shape the responses themselves for when writing and conducting integration tests.

Castle Mock can create mocked services based on WSDL, WADL, Swagger and RAML definition files. The web-services defined within the files will be mocked automatically by Castle Mock. Once the mocks for the web-services are created, they can be configured to mock the service or forward the request to the original endpoint. The response from the forwarded requests can be recorded automatically and used to create new mocked responses.

Castle Mock is completely free and open source (Apache License 2.0). It is built with Java and the application itself is deployed to an Apache Tomcat server.

## What to Use Castle Mock for and<br/>When to Use It
----

Use Castle Mock to mock out RESTful APIs and SOAP web services for testing purposes for when either performing system or integration tests. It is recommended to only use Castle Mock on an internal network and never be used publically. Castle Mock is **NOT** developed or meant for anything else other than for testing purposes.

## Download
----

<center>
<div>
<a href="https://github.com/castlemock/castlemock/releases/latest/download/castlemock.war"><button class="btn"><i class="fa fa-download"></i> Download</button></a>
</div>
<br/>

Castle Mock can be downloaded as Java Web Archive (.war) file and be deployed on a Apache Tomcat server (Apache Tomcat 8.0 or higher).  No additional configurations are required in order to get Castle Mock up and running.
</center>

## Use Castle Mock
----
<div class="preview-video">
	<center>
		<video width="400" height="350" loop autoplay muted>
			<source src="assets/video/preview.m4v" type="video/mp4">
		</video>
	</center>
</div>
Castle Mock can be accessed from the web browser when the installation is complete as such:

	http://localhost:8080/castlemock

This will prompt you the login screen. When logging for the first time use the following credentials:
	
	Username: admin 
	Password: admin

It is recommended that the administrator profile gets updated with a more secure password. This is accomplish by going to the user page and choosing to update the profile.

Upon successful login, you will be able to create both SOAP and REST projects. SOAP and REST resources can either be created manually or created by importing resource descriptions, such as WSDL and WADL. All created resources can be mocked multiple times. Each resource can also be configured to have different response strategies, such as random and sequence

## Castle Mock loves Docker
----

> Docker is an open-source project that automates the deployment of applications inside software containers, by providing an additional layer of abstraction and automation of operating-system-level virtualization on Linux.

Castle Mock absolutely loves Docker. Docker allows you to simply setup and deploy your own instance of Castle Mock, by just typing one line. Download and install Docker by visiting their web page: http://docker.com

Use our official Docker image to setup and test Castle Mock:

	docker run -d -p 8080:8080 castlemock/castlemock

Castle Mock can be accessed from the following address after the installation is finished

	http://localhost:8080/castlemock

For more information and details: <a href="https://hub.docker.com/r/castlemock/castlemock">https://hub.docker.com/r/castlemock/castlemock</a>

## Documentation
----

Documentation can be found under our [GitHub Wiki](https://github.com/castlemock/castlemock/wiki). 

## Bugs and Feedback
----

For bugs, questions and discussions please use the [GitHub Issues](https://github.com/castlemock/castlemock/issues)

## License
----

**Castle Mock** is **licensed** under the **[Apache License](https://github.com/castlemock/castlemock/blob/master/LICENSE)**. The terms of the license are as follows:

    Apache License

    Copyright 2015 Karl Dahlgren and a number of other contributors.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
