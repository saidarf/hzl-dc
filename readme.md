This module will start Hazelcast write a flag into cache
I'm assuming that not all the 10 modules need to be started before a module can write the message into the console.
(I've included a second method readWriteToCache(int, int) if the all the modules need to be up before the message is written)
Written using Spring Cache & Hazelcast. Can be replavced with any other JCache compatible layer.
