
|Test ID|Description|Exp I/P|Exp O/P|Actual O/P|Type Of Test|
|-----|------|-----|-----|-----|------|
|H_01|Check All the product price is entered|Id no|Price of Product|Priced Displayed|Requirement Based|
|H_02|Check Wheather the entered product is displayed or not|Id no|Product displayed|Product displayed|Scenario Based|
|H_03|Check the product Id no correct or not|Id no|Display product|Display product|Boundary Based|

|Test ID|Description|Exp I/P|Exp O/P|Actual O/P|Type Of Test|
|-----|------|-----|-----|-----|------|
|L_01|Check each product show its cost price|Id no|product with price|product with price|Requirement Based|
|L_02|Check Wheather the product cannot entered without quantity |Id no & qty|display product & qty|display product & qty|Scenario Based|
|L_03|Check when the user gives the Qty immediately it will multiply with price |Id no & qtp|Multiplied price|Multiplied price|Boundary Based|


## USAGE UNITY TEST FRAMEWORK:
The Unity Test Framework (UTF) enables Unity users to test their code in both Edit Mode and Play Mode, and also on target platforms such as Standalone, Android, iOS, etc.
UTF uses a Unity integration of NUnit library, which is an open-source unit testing library for .Net languages.
It is possible to extend the Unity Test Framework (UTF) in many ways, for custom workflows for your projects and for other packages to build on top of UTF.


## Best Practices

 - [x] Checked all the possibilities of output
 - [x] Mentioned all the inputs for better understanding
 - [x] Presented in tabular form for easy understanding
 - [x] Both High level and low level Test plans are shown
