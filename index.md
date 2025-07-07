<center><h1>Castle Mock</h1></center>
<center><h2>Mock REST APIs and SOAP web-services</h2></center>

<div style="border:1px solid #e00; padding:16px; background-color:#ffe6e6; color:#800; font-weight:bold;">
Castle Mock is no longer maintained and will not receive future updates.  
The GitHub repository remains available for reference, but we recommend exploring alternatives for active use. The Docker Hub repository will eventually be deprecated and deleted. 
Please see <a href="https://github.com/castlemock/castlemock/blob/master/DEPRECATION.md">DEPRECATION</a> for more information.
</div>

----

<div> 
<p align="center">
    <a href="LICENSE"><img src="https://img.shields.io/badge/license-Apache%202-blue.svg"></a>
    <img src="https://img.shields.io/badge/status-unmaintained-red">
</p>
</div>

----

**Castle Mock** is a web application that provides the functionality to mock out RESTful APIs and SOAP web-services. This functionality allows client-side developers to completely mimic a server side behavior and shape the responses themselves for when writing and conducting integration tests.

Castle Mock can create mocked services based on WSDL, WADL, Swagger and RAML definition files. The web-services defined within the files will be mocked automatically by Castle Mock. Once the mocks for the web-services are created, they can be configured to mock the service or forward the request to the original endpoint. The response from the forwarded requests can be recorded automatically and used to create new mocked responses.

Castle Mock is completely free and open source (Apache License 2.0). It is built with Java and the application itself is deployed to an Apache Tomcat server.

## What to Use Castle Mock for and<br/>When to Use It
----

Use Castle Mock to mock out RESTful APIs and SOAP web services for testing purposes for when either performing system or integration tests. It is recommended to only use Castle Mock on an internal network and never be used publically. Castle Mock is **NOT** developed or meant for anything else other than for testing purposes.


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

## Documentation
----

Documentation can be found under our [GitHub Wiki](https://github.com/castlemock/castlemock/wiki). 

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
