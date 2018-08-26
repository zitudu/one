<!---
 Copyright (c) 2018 zitudu
 
 This software is released under the MIT License.
 https://opensource.org/licenses/MIT
-->

# One

[![Build Status](https://travis-ci.org/zitudu/one.svg?branch=master)](https://travis-ci.org/zitudu/one)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/zitudu/one/blob/master/LICENSE)

`One` is a cross-clouds running on runc file system that saves objects with taggings.

# Roles

- `api`: interacts with file system.

- `registy`: service discovery.

- `cmdb`: configuration server for resources.

- `runner`: runners executes tasks on dispatched resources.