..
      Copyright 2010 United States Government as represented by the
      Administrator of the National Aeronautics and Space Administration. 
      All Rights Reserved.

      Copyright 2010 Anso Labs, LLC

      Licensed under the Apache License, Version 2.0 (the "License"); you may
      not use this file except in compliance with the License. You may obtain
      a copy of the License at

          http://www.apache.org/licenses/LICENSE-2.0

      Unless required by applicable law or agreed to in writing, software
      distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
      WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
      License for the specific language governing permissions and limitations
      under the License.

Nova Binaries
===============

* nova-api
* nova-compute
* nova-manage
* nova-objectstore
* nova-volume

The configuration of these binaries relies on "flagfiles" using the google 
gflags package. If present, the nova.conf file will be used as the flagfile 
- otherwise, it must be specified on the command line::
   
   $ python node_worker.py --flagfile flagfile