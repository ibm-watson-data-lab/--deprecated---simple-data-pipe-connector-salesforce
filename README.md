# Simple Data Pipe Connector for Salesforce

##### [Simple Data Pipe](https://developer.ibm.com/clouddataservices/simple-data-pipe/) connector for [salesforce.com](http://www.salesforce.com)

This repository contains the Salesforce Simple Data Pipe connector. The connector should be used with latest version of the Simple Data Pipe implementing the [Simple Data Pipe SDK](https://github.com/ibm-cds-labs/simple-data-pipe-sdk).

Need to load data from other sources? Check out the [connector repository](https://developer.ibm.com/clouddataservices/simple-data-pipe-connectors/).

### Pre-requisites

##### General

To load data from Salesforce you need to have an account with Admin permissions. For details on how to configure the Simple Data Pipe application in the Salesforce web console, refer to the (tutorial)[https://developer.ibm.com/clouddataservices/simple-data-pipe-salesforce-looker/).

##### Deploy the Simple Data Pipe

  [Deploy the Simple Data Pipe in Bluemix](https://github.com/ibm-cds-labs/simple-data-pipe) using the Deploy to Bluemix button or manually.

##### Install the Stripe.com connector

  Install the connector using [these instructions](https://github.com/ibm-cds-labs/simple-data-pipe/wiki/Installing-a-Simple-Data-Pipe-Connector) into the Simple Data Pipe.  

### Using the salesforce.com Connector 

To load CRM information from salesforce.com:

* Select __SalesForce__ for the _Type_ when creating a new pipe.  
* In the _Connect_ page, enter the __OAuth consumer key__ and __consumer secret__ from the salesforce application page.
* Click __Connect to SalesForce__.
* If prompted to authenticate, log in using your salesforce credentials.
* Grant the Simple Data Pipe read access to your data.
* In the _Filter data_ page, select __All tables__ to load data for all supported tables or a single table to load a subset of data.
* Schedule a pipe run or run the pipe immediately.

#### License 

Copyright [2015-2016] IBM Cloud Data Services

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
