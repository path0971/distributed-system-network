Prerequisite: you should configure your distributed server such as Zookeeper.

Before using these files in this repository, you should prepare "Protocol Buffer" which is a library that provides you with an efficiency and elasticity 
of communications among your services. I used Protoc-3.7.1 and worked well .

In the httpserver folder, there's a web server that uses port 8080.

In the httpclient folder, there are Aggregator and Application.

They send workloads to the worker nodes through network. By integrating these two into a jar file 
enables you to distribute the workloads to several worker nodes and get results as a process for clients
