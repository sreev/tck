1105-feel-upper-case-function
--------------------

### Description ###

DMN Model [1105-feel-upper-case-function.dmn](./1105-feel-upper-case-function.dmn) tests DMN specification conformance of `FEEL built-in function 'upper case(string)`. Tested category is `string functions`.

#### Specification Reference(s): ####
 * DMN 1.1 - 10.3.4.3 Table 60

### Test Cases ###

|Decision Name| Literal Expression (FEEL) | Expected Result (Expected Type)|
|-------------|-------------------------- |--------------------------------|
|feel-upper-case-function_001_2395aaad55|upper case("a")|"A" (string)|
|feel-upper-case-function_002_991789dded|upper case("abc")|"ABC" (string)|
|feel-upper-case-function_003_d8306d8d00|upper case("")|"" (string)|
|feel-upper-case-function_004_310caf7262|upper case("1")|"1" (string)|
|feel-upper-case-function_005_b316d773ac|upper case("?@{")|"?@{" (string)|
|feel-upper-case-function_006_d9bd3c14bc|upper case(string:"AbDcF")|"ABDCF" (string)|
|feel-upper-case-function_007_31fc6c1967|upper case(string:"xyZ ")|"XYZ " (string)|
|feel-upper-case-function_008_26e369a9d9|upper case(string:"123ABC")|"123ABC" (string)|

         

### Disclaimer ###
This page is a simple view for the underlying DMN model file [1105-feel-upper-case-function.dmn](./1105-feel-upper-case-function.dmn).
The purpose of the model is to test and validate FEEL expressions. Therefore the underlying DMN model is simplistic:
Each decision node contains one literal expression under test. The table above shows the decision, the underlying FEEL expression and the expected result.

Site generated by [ACTICO GmbH](https://actico.com) for [Technology Compatibility Kit (TCK)](https://dmn-tck.github.io/tck/) for the Decision Model and Notation (DMN) standard.

[DMN 1.1. Specification Document](http://www.omg.org/spec/DMN/1.1/) 
  