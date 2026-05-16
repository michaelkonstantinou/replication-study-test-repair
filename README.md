# Replication package: The Importance of accounting for Content-based Test Repair in LLM-based test generation

This is a repository that contains all information required to replicate the study "The Importance of accounting for Content-based Test Repair in LLM-based test generation"

## Overview

The package is using a test repair mechanism and 5 baselines of which this mechanism was applied too. 

When it comes to the **test-repair mechanism**, the implementation lies in the CompilationFixing and OracleFixing components of the following repository. Keep in mind, that this repository contains also the variation **LLM-Plain + Test Repair**: https://github.com/michaelkonstantinou/yate-java

For the **rest of the baselines used**, you need to find the implementation of **ChatUniTest** (It is openly available on Github). If you are looking for our variation which integrates the Test-Repair approach to the baselines found in ChatUniTest, you may find our variation in the links below
- [Chatunitest-core-with-test-repair](https://github.com/michaelkonstantinou/chatunitest-core-with-yate)
- [Chatunittest-plugin-with-test-repair](https://github.com/michaelkonstantinou/chatunitest-maven-plugin-with-yate)
