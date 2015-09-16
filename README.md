portfolio-item-copy
=========================

## Overview

This app copies a portfolio item and all it's children, including other portfolio items, user stories (including user story hierarchies), tasks, and test cases. There are a couple of items to note.  There is an asynchronous thread that reports the stats (item counts) before the copy occurs and sometimes comes up short on the count, but the copy is correct. There is also a 300 item child limit on tasks and test cases.

Currently it only copies the following fields, but are configurable around line 22 of App-uncompressed.html.
- Name
- Description
- Owner
- Parent
- Tags

![alt text](https://raw.githubusercontent.com/RallyRonnie/portfolio-item-copy/master/screenshot.png "Screenshot")


## License

AppTemplate is released under the MIT license.  See the file [LICENSE](./LICENSE) for the full text.

##Documentation for SDK

