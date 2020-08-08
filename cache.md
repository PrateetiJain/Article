# Different Caching Approaches To Improve Performance and Scalability

## Introduction

In this report, we will learn about how different caching approaches affect performance of application. We will learn about advantages and disadvantages of Cache-aside, Read-through, Write-through, and  Write-behind Caching.

First we will study about where we can implement caching. So, it can be implemented at various levels like at client, server, and database etc.

### 1. Client Caching : 

In client-caching files are stored at in local cache memory of the client computer, it helps to improve speed. When client read data for first time it read data from server and save that to local cache, if client need same data again, it is takem from cache. 

### 2. Database Caching :
### 3. Web-Browser:
### 4. 

There are different type of cache strategies:

### 1. Cache-Aside :
### 2. Write-Through:
### 3. Read-Through:
### 4. Write-aside:

This is the most used cache strategy in application. In this, Application first asked  data in cache, if not found then search in Repository. Repository return data then application saves this data in cahche memory also. And when Applcation writes data it save it in both cache and repository.

![Cache-Aside](/images/cacheaside.png)




### advantages-disadvantages;
### comparision
### conclusion



