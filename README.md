# DockerQA: Docker-based Generic Enablers Quality Assurance
This document describes the DockerQA service developed at ITESM as a tool for verifying the correct deployment of the Docker-based Generic Enablers from the [FIWARE catalogue](https://www.fiware.org/developers/catalogue/).

[FIWARE](https://www.fiware.org/) is a curated framework of open source platform components to accelerate the development of Smart solutions. The [FIWARE platform](https://www.fiware.org/developers/catalogue/) provides a rather simple yet powerful set of APIs (Application Programming Interfaces) that ease the development of Smart Applications in multiple vertical sectors. 

The main and only mandatory component of any "Powered by FIWARE" platform or solution is the [FIWARE Orion Context Broker Generic Enabler](https://fiware-orion.readthedocs.io/en/master/), which brings a cornerstone function in any smart solution: the need to manage context information in a highly decentralized and large-scale manner, enabling to perform updates and bring access to context.

The Context Broker in turn is surrounded by a suite of additional platform components (called [Generic Enablers](https://catalogue-server.fiware.org/enablers)), which may be supplying context data (from diverse sources such as a CRM system, social networks, mobile apps or IoT sensors for example), supporting processing, analysis and visualization of data or bringing support to data access control, publication or monetization.

The Generic Enablers integrated into the DockerQA service are:
1. [Orion Context Broker](https://fiware-orion.readthedocs.io/en/master/)
1. [Application Mashup - Wirecloud](https://wirecloud.readthedocs.io/en/stable/)
1. [Data Visualization - Knowage](https://knowage.readthedocs.io/en/latest/)
1. [Stream Oriented - Kurento](https://kurento.readthedocs.io/en/stable/)
1. [Identity Management - KeyRock](https://fiware-idm.readthedocs.io/en/latest/)
1. [PEP Proxy - Wilma](https://fiware-pep-proxy.readthedocs.io/en/latest/)
1. [Authorization PDP - AuthzForce](https://authzforce-ce-fiware.readthedocs.io/en/latest/)
1. [IoT Broker - AERON](https://fiware-iot-broker.readthedocs.io/en/master/)
1. [Proactive Technology Online - Proton](https://proactive-technology-online.readthedocs.io/en/latest/index.html)
1. [GIS Data Provider - GeoServer](https://gisdataprovider.readthedocs.io/en/latest/index.html)

A complete list of FIWARE Generic Enablers can be consulted at the [official FIWARE Catalogue web page](https://catalogue-server.fiware.org/) and at the [FIWARE Catalogue documentation page](https://www.fiware.org/developers/catalogue/).

## Prerequisites
A computer or smart-device with a web browser and access to the Internet.

## How to use
Access the service via the [DockerQA official website](http://148.241.3.246:3800/)
![1](https://user-images.githubusercontent.com/39604832/51412805-7fec0600-1b32-11e9-9acb-5176dbb94b65.PNG)

## A walkthrough
The main functionalities concentrated into the DockerQA service are:
1. [Test one Generic Enabler](https://github.com/ITESM-FIWARE/Docker-based-Generic-Enablers-Quality-Assurance#test-one-generic-enabler)
1. [Test two or more Generic Enablers](https://github.com/ITESM-FIWARE/Docker-based-Generic-Enablers-Quality-Assurance#test-two-or-more-generic-enablers)
1. [Test all Generic Enablers](https://github.com/ITESM-FIWARE/Docker-based-Generic-Enablers-Quality-Assurance#test-all-generic-enablers)
1. [Visualize the general reports of all Generic Enablers](https://github.com/ITESM-FIWARE/Docker-based-Generic-Enablers-Quality-Assurance#visualize-the-general-reports-of-all-generic-enablers)
1. [Visualize specific reports of a selected Generic Enabler](https://github.com/ITESM-FIWARE/Docker-based-Generic-Enablers-Quality-Assurance#visualize-specific-reports-of-a-selected-generic-enabler)

### Test one Generic Enabler
This section describes the step-by-step procedure to test one Generic Enabler integrated into the DockerQA service.

1. In the main page of the service, select the Aeron Generic Enabler
![1](https://user-images.githubusercontent.com/39604832/51412805-7fec0600-1b32-11e9-9acb-5176dbb94b65.PNG)
![2](https://user-images.githubusercontent.com/39604832/51412806-7fec0600-1b32-11e9-868c-d2d9515c8cbb.PNG)
1. Press the "Test the selected GE" button at the left-top side of the page
![3](https://user-images.githubusercontent.com/39604832/51412807-7fec0600-1b32-11e9-81dd-4880507c1548.PNG)
1. The test process of the Generic Enabler may take several minutes
![4](https://user-images.githubusercontent.com/39604832/51412808-80849c80-1b32-11e9-925b-aa818cc9b33f.PNG)
1. Once the test process are finished, a report of the test in JSON format is deployed in a new window
![5](https://user-images.githubusercontent.com/39604832/51412809-80849c80-1b32-11e9-805a-ab82a804e98f.PNG)
1. If the user presses the "User" button at the top of the page, in the report window, the same report is displayed in a "certificate" format
![6](https://user-images.githubusercontent.com/39604832/51412810-80849c80-1b32-11e9-9bd4-03870fa26a5d.PNG)
1. Both reports can be downloaded by pressing the green button at the right-top side of the page
![7](https://user-images.githubusercontent.com/39604832/51412811-80849c80-1b32-11e9-84a5-48416515504e.PNG)

### Test two or more Generic Enablers
This section describes the step-by-step procedure to test two or more Generic Enablers integrated into the DockerQA service without testing all Generic Enablers available in the service, this last procedure will be explained in the next section.

1. In the main page of the service, select the Keyrock Generic Enabler and the Orion Context Broker Generic Enabler
![1](https://user-images.githubusercontent.com/39604832/51412805-7fec0600-1b32-11e9-9acb-5176dbb94b65.PNG)
![8](https://user-images.githubusercontent.com/39604832/51412812-80849c80-1b32-11e9-8ca7-81c4a997c164.PNG)
1. Press the "Test the selected GE" button at the left-top side of the page
![9](https://user-images.githubusercontent.com/39604832/51412814-80849c80-1b32-11e9-952c-75aa35179e18.PNG)
1. The test processes of the Generic Enablers may take several minutes
![10](https://user-images.githubusercontent.com/39604832/51412815-811d3300-1b32-11e9-9570-9e29a22c4087.PNG)
![11](https://user-images.githubusercontent.com/39604832/51412816-811d3300-1b32-11e9-803d-528864406130.PNG)
1. Once the test processes are finished, a report of each test in JSON format is deployed in a new window. The navigation through diverse reports is available via the "hands" buttons
![12](https://user-images.githubusercontent.com/39604832/51412817-811d3300-1b32-11e9-8fb6-fc9f79e6eb9a.PNG)
![13](https://user-images.githubusercontent.com/39604832/51412818-811d3300-1b32-11e9-8a46-551c4fccff6a.PNG)
1. If the user presses the "User" button at the top of the page, in the report window, the same report is displayed in a "certificate" format
1. Both reports can be downloaded by pressing the green button at the right-top side of the page

### Test all Generic Enablers
This section describes the step-by-step procedure to test all Generic Enablers integrated into the DockerQA service.

1. In the main page of the service, select all available Generic Enablers or press the "Test All Generic Enablers" button at the left-top side of the page
![1](https://user-images.githubusercontent.com/39604832/51412805-7fec0600-1b32-11e9-9acb-5176dbb94b65.PNG)
![14](https://user-images.githubusercontent.com/39604832/51412820-811d3300-1b32-11e9-9a82-b9de24b85a7d.PNG)
![15](https://user-images.githubusercontent.com/39604832/51412821-811d3300-1b32-11e9-8908-8a5a4ac6afd3.PNG)
![16](https://user-images.githubusercontent.com/39604832/51412822-811d3300-1b32-11e9-9634-be1a54e7f59e.PNG)
1. The test processes of all Generic Enablers may take several minutes
1. Once the test processes are finished, a report of each test in JSON format is deployed in a new window. The navigation through diverse reports is available via the "hands" buttons
1. If the user presses the "User" button at the top of the page, in the report window, the same report is displayed in a "certificate" format
1. Both reports can be downloaded by pressing the green button at the right-top side of the page

### Visualize the general reports of all Generic Enablers
This section describes the step-by-step procedure to visualize all the test reports generated by all tests of the Generic Enablers integrated into the DockerQA service.

1. In the main page of the service, select the option "General Reports" in the "Menu bar" located at the left side of the page
![1](https://user-images.githubusercontent.com/39604832/51412805-7fec0600-1b32-11e9-9acb-5176dbb94b65.PNG)
![17](https://user-images.githubusercontent.com/39604832/51412823-81b5c980-1b32-11e9-82a5-f73e9e10c708.PNG)
1. A window with all reports of all tested Generic Enablers will be displayed
![18](https://user-images.githubusercontent.com/39604832/51412824-81b5c980-1b32-11e9-9686-dbc85f8cbffe.PNG)

### Visualize specific reports of a selected Generic Enabler
This section describes the step-by-step procedure to visualize all the test reports generated by a specific Generic Enabler integrated into the DockerQA service.

1. In the main page of the service, select the option "Specific Report" in the "Menu bar" located at the left side of the page
![1](https://user-images.githubusercontent.com/39604832/51412805-7fec0600-1b32-11e9-9acb-5176dbb94b65.PNG)
![19](https://user-images.githubusercontent.com/39604832/51412825-81b5c980-1b32-11e9-9297-0048326afecb.PNG)
1. Select the Geoserver Generic Enabler
![20](https://user-images.githubusercontent.com/39604832/51412826-81b5c980-1b32-11e9-8273-c8bb33d8c807.PNG)
1. A window with all reports of the selected Generic Enabler will be displayed
![21](https://user-images.githubusercontent.com/39604832/51412827-81b5c980-1b32-11e9-8169-d1f11c310711.PNG)
