<h1>Expanded Capabilities: Advanced Arithmetic Operations</h1>

we have expanded the capabilities of the calculator microservice by introducing support for advanced arithmetic operations 
such as exponentiation, square root, and modulo operations. We have implemented corresponding API endpoints to handle these operations, 
thereby enriching the functionality of the microservice and providing users with more comprehensive calculation capabilities.

**Updated Features**
* Added support for exponentiation, square root calculation, and modulo operations.
* Implemented corresponding API endpoints to handle these advanced arithmetic operations.
* Enhanced error handling and logging to accommodate the new functionalities.

**API Endpoints**

* Exponentiation
  * Endpoint: /power
  * Method: GET
  * Parameters:
     * base: Numeric value representing the base.
     * exponent: Numeric value representing the exponent.
  * Example request: http://localhost:3040/power?base=2&exponent=3
  * Example response:
  * <img width="137" alt="Screenshot 2024-04-08 at 3 18 13 pm" src="https://github.com/gaurav3444/sit323-737-2024-t1-prac4c/assets/66586901/44fa94b3-5056-48a1-b093-b77c343e05bd">


* Square Root
  * Endpoint: /sqrt
  * Method: GET
  * Parameters:
     * number: Numeric value for which square root needs to be calculated.
  * Example request: http://localhost:3040/sqrt?number=16
  * Example response:
  * <img width="149" alt="Screenshot 2024-04-08 at 3 18 40 pm" src="https://github.com/gaurav3444/sit323-737-2024-t1-prac4c/assets/66586901/3fceef1e-c11b-4486-b08d-744a5d9c26b3">



* Modulo Operation
  * Endpoint: /modulo
  * Method: GET
  * Parameters:
     * dividend: Numeric value representing the dividend.
     * divisor: Numeric value representing the divisor.
  * Example request: http://localhost:3040/modulo?dividend=10&divisor=3
  * Example response:
  * <img width="150" alt="Screenshot 2024-04-08 at 3 19 26 pm" src="https://github.com/gaurav3444/sit323-737-2024-t1-prac4c/assets/66586901/1f309bf7-bf2e-4584-a66d-11db1e1ff107">

**Terminal output**
* <img width="810" alt="Screenshot 2024-04-08 at 3 21 01 pm" src="https://github.com/gaurav3444/sit323-737-2024-t1-prac4c/assets/66586901/78d49bf8-00aa-41ee-bfa1-34f19510207f">
