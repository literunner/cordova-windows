<!--
#
# Licensed to the Apache Software Foundation (ASF) under one
# or more contributor license agreements.  See the NOTICE file
# distributed with this work for additional information
# regarding copyright ownership.  The ASF licenses this file
# to you under the Apache License, Version 2.0 (the
# "License"); you may not use this file except in compliance
# with the License.  You may obtain a copy of the License at
# 
# http://www.apache.org/licenses/LICENSE-2.0
# 
# Unless required by applicable law or agreed to in writing,
# software distributed under the License is distributed on an
# "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
#  KIND, either express or implied.  See the License for the
# specific language governing permissions and limitations
# under the License.
#
-->

Apache Cordova for Windows universal (8.1)
===

[![Build status](https://ci.appveyor.com/api/projects/status/30ax1dqow7yromjh/branch/master-nufix?svg=true)](https://ci.appveyor.com/project/brodybits/cordova-windows-universal-fix/branch/master-nufix)

Includes Windows universal app template to build [Apache Cordova](http://cordova.apache.org) applications that target Windows 8.1 and Windows Phone 8.1. An Apache Cordova based applications is, at the core, an application written with web technology: HTML, CSS and JavaScript.

[Apache Cordova](http://cordova.apache.org) is a project of [The Apache Software Foundation (ASF)](http://apache.org)

This fork supports *all* Windows 8.1 and Windows Phone 8.1 target platforms, as a solution to [CB-8866](https://issues.apache.org/jira/browse/CB-8866) and [CB-8869](https://issues.apache.org/jira/browse/CB-8869).

Requires
---

**To build for all platforms** (Windows 8.1 and Windows Phone 8.1)

  Windows 8.1 along with [Visual Studio 2013 Express](http://www.visualstudio.com/downloads/download-visual-studio-vs#d-express-windows-8) (or better).

Installation
------------

Install Cordova CLI:

    npm install -g cordova

Install cordova-windows from this fork:

    npm install -g litehelpers/cordova-windows_universal_fix

NOTE: it is also possible to create a Windows Universal (8.1) project by cloning this repository and then:

    path.to.cordova-windows_universal_fix\bin\create.bat your.project.path your.package.name YourAppName

Then you can use a very recent version of plugman to install Windows (Universal)-enabled plugins.

BUGS?
-----

- For this fork *only*: https://github.com/litehelpers/cordova-windows_universal_fix/issues

Further Reading
---

- [Windows Platform Guide](http://cordova.apache.org/docs/en/edge/guide_platforms_win8_index.md.html#Windows%208%20Platform%20Guide)
- [Apache Cordova Documentation](http://docs.cordova.io)
