# etcd client API example

A simple application that can interface with most features of ectd.

So far, there is an event watching system that allows for single blocking event watch and an Event stream watcher. The stream
requeries the same key using the 'next' index to ensure that the stream never drops an event. Both cases, the APi allows
for recursive watching of a tree or a single node.

Now supports basic Set/Get of a value in etcd. The node must exist. Next is node management and listing

