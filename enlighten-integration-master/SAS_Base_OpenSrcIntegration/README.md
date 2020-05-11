/******************************************************************************

Copyright (c) 2015 by SAS Institute Inc., Cary, NC 27513 USA

Licensed under the Apache License, Version 2.0 (the "License"); 
you may not use this file except in compliance with the License. 
You may obtain a copy of the License at 

   http://www.apache.org/licenses/LICENSE-2.0 

Unless required by applicable law or agreed to in writing, software 
distributed under the License is distributed on an "AS IS" BASIS, 
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. 
See the License for the specific language governing permissions and 
limitations under the License.  

******************************************************************************/

Open Source Integration Using the Base SAS Java Object

===============

Code and materials for integrating open source packages with SAS 

using the Base SAS Java Object.

To accompany "Open Source Integration Using the Base SAS Java Object":

https://support.sas.com/rnd/app/data-mining/enterprise-miner/pdfs/SAS_Base_OpenSrcIntegration.pdf



These examples were tested in the following environment:

Windows 7 Professional Workstation

16 GB RAM 

SAS 9.4 (TS1M2)

Anaconda Python 2.7

R 3.1.2

Oracle JDK 1.7.0_25

NOTE: This project was compiled with Oracle JDK 1.7.0_25. We highly recommend using Java 7 to compile the java files in this project. 
When class files generated by some versions of Java 8 are used, the Base SAS Java Object fails with the following error:

ERROR: Could not find class dev.SASJavaExec at line 35 column 20.  Please ensure that the CLASSPATH is correct.
ERROR: DATA STEP Component Object failure.  Aborted during the EXECUTION phase.
java.lang.UnsupportedClassVersionError: dev/SASJavaExec : Unsupported major.minor version 52.0
