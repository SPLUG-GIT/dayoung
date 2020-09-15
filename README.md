
## Latest Release (2020/09/09)

We're happy to announce the release of Pinpoint v2.1.0.
Please check the release note at (https://github.com/naver/pinpoint/releases/tag/v2.1.0).

The current stable version is [v2.1.0](https://github.com/naver/pinpoint/releases/tag/v2.1.0).

## Live Demo

Take a quick look at Pinpoint with our [demo](http://125.209.240.10:10123/main/ApiGateway@SPRING_BOOT/5m?inbound=1&outbound=4&wasOnly=false&bidirectional=false)!

## PHP, PYTHON

Pinpoint also supports application written in PHP, Python. [Check-out our agent repository](https://github.com/naver/pinpoint-c-agent).

## About Pinpoint

**Pinpoint** is an APM (Application Performance Management) tool for large-scale distributed systems written in Java / [PHP](https://github.com/naver/pinpoint-c-agent)/[PYTHON]((https://github.com/naver/pinpoint-c-agent)).
Inspired by [Dapper](http://research.google.com/pubs/pub36356.html "Google Dapper"),
Pinpoint provides a solution to help analyze the overall structure of the system and how components within them are interconnected by tracing transactions across distributed applications.

You should definitely check **Pinpoint** out If you want to

* understand your *[application topology](https://naver.github.io/pinpoint/overview.html#overview)* at a glance
* monitor your application in *Real-Time*
* gain *code-level visibility* to every transaction
* install APM Agents *without changing a single line of code*
* have minimal impact on the performance (approximately 3% increase in resource usage)

## Getting Started
 * [Quick-start guide](https://naver.github.io/pinpoint/quickstart.html) for simple test run of Pinpoint
 * [Installation guide](https://naver.github.io/pinpoint/installation.html) for further instructions.
## Overview

Services nowadays often consist of many different components, communicating amongst themselves as well as making API calls to external services. How each and every transaction gets executed is often left as a blackbox. Pinpoint traces transaction flows between these components and provides a clear view to identify problem areas and potential bottlenecks.  
For a more intimate guide, please check out our  _[Introduction to Pinpoint](http://naver.github.io/pinpoint/#want-a-quick-tour)_  video clip.

-   **ServerMap**  - Understand the topology of any distributed systems by visualizing how their components are interconnected. Clicking on a node reveals details about the component, such as its current status, and transaction count.
    
-   **Realtime Active Thread Chart**  - Monitor active threads inside applications in real-time.
    
-   **Request/Response Scatter Chart**  - Visualize request count and response patterns over time to identify potential problems. Transactions can be selected for additional detail by  **dragging over the chart**.
    
    [![Server Map](https://github.com/naver/pinpoint/raw/master/doc/images/ss_server-map.png)](https://github.com/naver/pinpoint/blob/master/doc/images/ss_server-map.png)
    
-   **CallStack**  - Gain code-level visibility to every transaction in a distributed environment, identifying bottlenecks and points of failure in a single view.
    
    [![Call Stack](![20200911193717_3b0e98be46d692da7aab09c1bb0834c0_jv1c](https://user-images.githubusercontent.com/53688895/93166890-601f4200-f75a-11ea-82f1-6231c0bcbd98.jpeg)
)](https://github.com/naver/pinpoint/blob/master/doc/images/ss_call-stack.png)
    
-   **Inspector**  - View additional details on the application such as CPU usage, Memory/Garbage Collection, TPS, and JVM arguments.

![다운로드](https://user-images.githubusercontent.com/53688895/93166975-8fce4a00-f75a-11ea-817f-775a24b5e9eb.png)

## Supported Modules

* JDK 6+
* [naver](https://www.naver.com/)

## Compatibility

Java version required to run PinPoint:

Pinpoint version | Agent | Collector | Web
---------------- | ----- | --------- | ---
1.5.x  | 6-8  | 7-8 | 7-8
1.6.x  | 6-8  | 7-8 | 7-8
1.7.x  | 6-8  | 8   | 8
1.8.0  | 6-10 | 8   | 8
1.8.1+ | 6-11 | 8   | 8
2.0.x  | 6-13 | 8   | 8
2.1.x  | 6-14 | 8   | 8

## Commuunity
[Github issues]()
[Google group]()
[Glitter]()

We have Chinese community now, welcome to join!

QQ Group1: 897594820

QQ Group2: 812507584

DING Group

[![QQ Group1](https://github.com/naver/pinpoint/raw/master/doc/images/NAVERPinpoint.png)](https://github.com/naver/pinpoint/blob/master/doc/images/NAVERPinpoint.png)

[![QQ Group2](https://github.com/naver/pinpoint/raw/master/doc/images/NAVERPinpoint2.png)](https://github.com/naver/pinpoint/blob/master/doc/images/NAVERPinpoint2.png)

[![DING Group](https://github.com/naver/pinpoint/raw/master/doc/images/NaverPinpoint%E4%BA%A4%E6%B5%81%E7%BE%A4-DING.jpg)](https://github.com/naver/pinpoint/blob/master/doc/images/NaverPinpoint%E4%BA%A4%E6%B5%81%E7%BE%A4-DING.jpg)

## License

Pinpoint is licensed under the Apache License, Version 2.0. See  [LICENSE](https://github.com/naver/pinpoint/blob/master/LICENSE)  for full license text.

```
Copyright 2018 NAVER Corp.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
