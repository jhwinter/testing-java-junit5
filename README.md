[![CircleCI](https://dl.circleci.com/status-badge/img/circleci/Ln7qGzxo5A3f4ZQpoohvpT/6PFEtzFwGA3YmZeSHgWTC2/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/circleci/Ln7qGzxo5A3f4ZQpoohvpT/6PFEtzFwGA3YmZeSHgWTC2/tree/main)
# Introduction to JUnit 5 with Maven

All source code examples in the repository are for my [Online Course - Testing Spring Beginner to Guru](https://www.udemy.com/testing-spring-boot-beginner-to-guru/?couponCode=GITHUB_REPO)

This source code repository contains JUnit 5 test examples with Maven.

## Setup
### Requirements
* Should use Java 11 or higher. Previous versions of Java are un-tested.
* Use Maven 3.5.2 or higher

## Support
For questions and help:
* Please post in course
* Or post in the Slack Community exclusive to the course.

GitHub Issues will not be addressed.



## Notes

### JUnit Assertion Lambdas

* JUnit 5 incorporates support of lambdas in assertions
* Grouped Assertions - all assertions run in block, all failures reported
* Dependent Assertions - allows for block of grouped assertions
* Expected exceptions are tested with assertThrows lambda expression
* Timeouts are tested with assertTimeout lambda expression

### Assertion Frameworks

* Popular Options
  * AssertJ (newer)
  * Hamcrest (older)
