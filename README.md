# User Management Application, Spring Boot, Ionic 4, MySQL, Hibernate, Liquibase

The application structure is as follows.
- **server-user-management** - Microservice implemented using Spring boot. [More info](server-user-management/README.md)
- **client-user-management** - Client Web Application implemented using with Angular 7. [More info](client-user-management/README.md)
- **mobile-user-management** - Mobile Application implemented using with Ionic 4. [More info](mobile-user-management/README.md)

### Build

#### 1) Build server-user-management

```
$ cd server-user-management
$ gradlew bootJar
$ gradlew bootRun
```

### Access server side using following URL

```
http://localhost:8080
```

#### 2) Build client-user-management

```
$ cd client-user-management
$ ng serve
```

### Access client side using following URL

```
http://localhost:4200
```

#### 3) Build mobile-user-management

```
$ cd mobile-user-management
$ ionic serve
```

### Access mobile side using following URL

```
http://localhost:8100
```

