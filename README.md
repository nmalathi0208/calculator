Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

[![Build Status](https://dev.azure.com/mamtajha/calculator-github/_apis/build/status/mamtajha-ts.calculator%20(2)?branchName=refs%2Fpull%2F6%2Fmerge)](https://dev.azure.com/mamtajha/calculator-github/_build/latest?definitionId=112&branchName=refs%2Fpull%2F6%2Fmerge)

To build, simply:
1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

