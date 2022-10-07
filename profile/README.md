# go-Seidon
The complete storage manager solution for your system

![go-Seidon logo][goseidon-logo]

With help of the other `kings` around the `ocean`, he is considered as one of the greatest storage managers. 

He can manage your application files which spread over the internet.

## 🚀 Motivations
1. Provide single point of entry to upload, manage and access the uploaded files.

## 🦄 Features
1. Multiple storage provider
- current support is: `hippo`
2. Multiple database provider
- current supports are: `mysql`, `mongo`
3. Multiple transport provider
- current supports are: `rest`, `grpc`

## 🧐 Upcoming Features
1. storage chariot (agregator)
- file meta key-value (storing file related data such as: user_id, feature, category, etc)
2. storage provider: `aws-s3`, `g-storage`, `alicloud-oss`
3. file access control (visibility, meta, etc)
4. custom access (custom link with certain limitation such as access duration, attribute user_id, etc)
5. custom upload rule (size, extension, etc)
6. file replication
7. file backup 
8. upload & retrieval auto failover
9. dashboard monitoring (grafana + prometheus, export data through rest/grpc)
10. sdk (golang, javascript, php)
10. golang `chariot` middleware (mux, fiber, echo, gin)
11. golang `hippo` middleware (mux, fiber, echo, gin)

## 🤩 Nice to Have
1. database provider: `postgre`
2. file caching support
3. resize image capability (?width=720&height=480)
4. bulk file upload
5. `rack` provider grouping

## 👷🏻 Architecture
![System Architecture][architecture-image]

> *Leave better than you found it*


[goseidon-logo]: https://github.com/go-seidon/.github/blob/master/asset/go-seidon.png?raw=true
[architecture-image]: https://github.com/go-seidon/.github/blob/master/asset/system-architecture.jpg?raw=true

