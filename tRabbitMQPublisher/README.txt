Welcome to Talend tRabbitMQPublisher component 
=======================================================================

This component contributes to publish message to exchange on RabbitMQ. 
You can also create new exchange and new queue with entered name which is binded with queue and exchange. 
You can configure the appropriate option for exchange and queue like duration, auto-delete, exclusive, routing-key and etc.
It's also able to use arguments for detail operation. If your queue or exchange already exist by RabbitMQ server, you don't need to configure that. 
Message is packed that data of schematic columns will be serialized with header which is specifying length of column data.
Because of using column length header(Integer-4bytes), You don't no more have to use field separator for column.
Each columns is managed by type to support Talend schema type, Therefore you must be complied column type sequence of publisher when you receive data at consumer.
Being to support Talend type, It can able to send object which is Serializable by Java Serializable rule and to send object to consumer.  

If you want to design stream-based architecture which is part of Data-Streamer or DataLake-Synchronizer,
This component is best option for your system.

=======================================================================
Ver 1.00 notification.
=======================================================================
1. Optional execution with whether field length header or field delimiter.
2. When die no message mode, add function of waiting terminate seconds.  

=======================================================================
Ver 0.95 notification.
=======================================================================
1. Support Talend schema types.
2. Adding field length header(Integer 4bytes), No more need to use field separator.
3. Publish/Consume java Object type which can be serialized by Serializable. Anything to be serialized within java object.  



=======================================================================
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