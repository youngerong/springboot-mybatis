# SpringBoot-MyBatis

个框架就是为了减少这些不必要的工作。它集成了 **Spring Boot** 和 **MyBatis**，并实现了一个类似“书籍管理”的模块（支持 **RESTful API**）以供参考，框架简单易懂。完全可以根据自己的需要，修改这个框架，以实现自己想实现的功能。

首先，你应该要将这个代码库克隆到你的磁盘上，并进入此目录。启动命令行窗口，键入：

```
git clone https://github.com/ShawnyXiao/SpringBoot-MyBatis.git
cd SpringBoot-MyBatis
```

然后，启动应用（初次启动的话，这个过程会需要稍微久一点的时间）。在命令行窗口中键入：

```
mvn spring-boot:run
```

此时，你可以尝试发出一个 HTTP 请求。例如，利用浏览器向你的 Web 应用发出一个 HTTP GET 请求，在地址栏键入：

```
http://localhost:8080/books/1
```

你将会看到，你的 Web 应用通过 JSON 字符串来做出响应：

```json
{
  "id": 1,
  "name": "Math",
  "author": "hawk",
  "price": 68,
  "topic": "Sicence",
  "publishDate": 1425139202345,
  "bookStoreId": 1
}
```

## 技术

- Spring Boot
- MyBatis
- MySQL 
- Maven


