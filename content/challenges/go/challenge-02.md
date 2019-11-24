---
author: Elliot Forbes
date: 2018-03-19T11:05:52Z
desc: In this Challenge, you will be building a very simple Go HTTP server which will show off the stats you collect in the first Go Challenge.
image: golang.png
series:
  - go-challenges
tags:
  - go
title: Challenge 02 - Creating a Simple HTTP Server in Go
twitter: https://twitter.com/Elliot_F
---

> You will extend the application developed in the first challenge so that these statistics can be queried via a http request. 

This application will run indefinitely on a machine and expose information on given port and an endpoint such that when you hit http://localhost:9000/stats it will fetch and display the stats for that machine in JSON format.

#### Key Concepts

* You will gain an understanding of how to write a simple HTTP server in Go
* You will learn about how to marshal and unmarshal information into structs

<details>
  <summary>Tutorials</summary>
  
  The following tutorials should help you to complete this challenge:
  
  * [Creating a RESTful API in Go](https://tutorialedge.net/golang/creating-restful-api-with-golang/)
</details>

# Conclusion

Congratulations! You have successfully completed the second TutorialEdge Go challenge!