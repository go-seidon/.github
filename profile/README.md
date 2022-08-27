# go-Seidon
The complete storage manager solution for your application

![go-Seidon logo][goseidon-logo]

With help of the other `kings` around the `ocean`, He is considered as one of the king of storage managers. 
He can manage your application files which spread over the internet.

## 🚀 Motivations
1. Provide single point of entry to upload, manage and access the uploaded files.

## 🦄 Features
1. Multiple storage provider
- current support is: `local`
2. Multiple database provider
- current supports are: `mysql`, `mongo`
3. Multiple transport layer
- current suppoort is: `rest`

## 🧐 Upcoming Features
1. storage provider: `aws-s3`, `g-storage`, `alicloud-oss`
2. database provider: `postgre`
3. transport layer: `grpc`
4. file meta key-value 
- (storing file related data such as: user_id, feature, category, etc)
5. file access control 
- (visibility, meta, etc)
6. custom access 
- (custom link with certain limitation such as access duration, attribute user_id, etc)
7. resize image capability
- ?width=720&height=480
8. bucket customization
- auto failover
9. file replication
10. rule customization
- size, extension, etc
11. file caching support
12. dashboard monitoring
- grafana + prometheus
- export data through rest/grpc
13. sdk
- golang sdk
- javascript sdk
- php sdk
14. golang aggregator middleware
- gorilla/mux
- echo 
- gin
- fiber
15. golang local middleware

## 👷🏻 Architecture
![System Architecture][architecture-image]

> *Leave better than you found it*


[goseidon-logo]: https://github.com/go-seidon/.github/blob/master/asset/go-seidon.png?raw=true
[architecture-image]: https://github.com/go-seidon/.github/blob/master/asset/system-architecture.jpg?raw=true

