====
    Licensed to jclouds, Inc. (jclouds) under one or more
    contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  jclouds licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.
====

#
# this is a simple example command line client that creates a queue in all regions, then tracks performance of it
# 1. execute 'mvn install' to build the sample
# 2. invoke the jar, passing your aws credentials and the bucket you wish to create
# ex.
# java -jar target/jclouds-speedtest-sqs-jar-with-dependencies.jar $AWS_USER $AWS_PWD testqueue 1000
