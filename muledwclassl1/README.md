# muledwclass1
This Project walks through the MuleSoft Operators from the Mulesoft documentation portal.
Dataweave operators from MuleSoft Documentation can be tested through postman with below URL links.
The expected input is given below for each the Tests which users can try out. 
For more information about the functions and expected output you can check the reference link 
given in each of the transform components. 
For more information check the attached word documents in src/test/resources folder
--------------------------------------------------------------------------------------------------------------------------------------
Test 1: Maps the input xml data to a JSON array using map operator 
URL(Postman) : http://localhost:8084/muledwclass1?operator=map
Input Data:
<prices>
    <basic>9.99</basic>
    <premium>53</premium>
    <vip>398.99</vip>
</prices>
--------------------------------------------------------------------------------------------------------------------------------------
Test 2: Maps the input xml data to a JSON array using mapobject operator resuling in a new Object
URL(Postman) : http://localhost:8084/muledwclass1?operator=mapobject
Input Data:
<prices>
    <basic>9.99</basic>
    <premium>53</premium>
    <vip>398.99</vip>
</prices>
--------------------------------------------------------------------------------------------------------------------------------------
Test 3: Pulls the required key and values and places them in separate arrays
URL(Postman) : http://localhost:8084/muledwclass1?operator=pluck
Input Data:
<prices>
    <basic>9.99</basic>
    <premium>53</premium>
    <vip>398.99</vip>
</prices>
--------------------------------------------------------------------------------------------------------------------------------------
Test 4: Calls the various functions which can be tried out looking at the Mulesoft documentation links for more 
information.
URL(Postman) : http://localhost:8084/muledwclass1?operator=morefunctions
Input Data: No input data is required
--------------------------------------------------------------------------------------------------------------------------------------
Test 5: Calls the various Math functions which can be tried out looking at the Mulesoft documentation links for more 
information.
URL(Postman) : http://localhost:8084/muledwclass1?operator=math
Input Data: No input data is required
--------------------------------------------------------------------------------------------------------------------------------------
Test 6: Calls the various datetime functions which can be tried out looking at the Mulesoft documentation links for more 
information.
URL(Postman) : http://localhost:8084/muledwclass1?operator=datetime
Input Data: No input data is required
--------------------------------------------------------------------------------------------------------------------------------------
Test 7: Refer Mule configuration File named "dataweave-reuse"
This is a simple example showing how we can reuse dataweave functions etc. For more details please refer following link:
https://blogs.mulesoft.com/dev/training-dev/how-to-reuse-dataweave-code/
