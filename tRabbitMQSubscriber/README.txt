Welcome to Talend tRabbitMQSubscriber component
=======================================================================

This component can able to subscribe message from RabbitMQ. 
You can edit and apply schema for message to transform data to using of your needs. 
You can set option for constant run, else if you want to wait for continuous enqueue message, otherwise the component terminate when all message of queue be consumed. 
This component just can be used single for consuming message, but It can be using with tRabbitMQPublisher component a pair.
Because of using column length header(Integer-4bytes), You don't no more have to use field separator for column.
Each columns is managed by type to support Talend schema type, Therefore you must be complied column type sequence of publisher.
As supporting Talend type, It can able to receive object which is Serialized by Java Serializable rule.  

If you want to design stream-based architecture which is part of Data-Streamer or DataLake-Synchronizer,
This component is best option for your system.

=======================================================================
Ver 1.00 notification.
=======================================================================
1. Optional execution with whether field length header or field delimiter.
2. When die no message mode, add function of waiting terminate seconds.  

=======================================================================
Ver. 0.95 notification.
=======================================================================
1. Support Talend schema types.
2. Adding field length header(Integer 4bytes), No more need to use field separator.
3. Publish/Consume java Object type which can be serialized by Serializable. Anything to be serialized within java object.  



All of the artifact rights comply to APACHE LICENSE, VERSION 2.0. 
For more information of apache 2.0 license to http://www.apache.org/licenses/LICENSE-2.0

Copyright (c) 2019, Kooin Shin
All rights reserved.

If you may have something for this software better, please connect to chaos930@gmail.com.
And make your days better and better.

Licensing
=======================================================================

   This software is licensed under the terms you may find in the file 
   named "LICENSE.txt" in this directory.