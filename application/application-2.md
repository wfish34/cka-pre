## Know various ways to configure applications
一个简单的应用可以拆分成Deployment或者StatefulSet或者ReplicaSet等控制器。一个Pod内有多种方式，内含多个容器，可以通过多个容器合并到一个Pod的方式来实现很多应用的构建。

对于互相之间有依赖的，可以通过Dependency等方式去实现。对于有状态的应用，也可以用SatefulSet等方式去创建