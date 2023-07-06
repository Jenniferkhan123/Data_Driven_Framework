Feature of the project:

1 This project is able to automate, execute and validate.
   Rest : POST, PUT , PATCH , Delete and GET
   Soap : POST, GET

2 Contructed the requestbody using parameters took from an excelfile, I have created an common utilty class using ApachePOI to read data from excelsheet.

3 I have implemented this framework on the concepts of data driven and keyword driven.
  I have created 4 pacakages(request repository, common API methods, test classes and driver class)into the project in
  Request repository
  > PATCH Request Repository
  > POST Request Repository
  > PUT Request Repository
  Common API methods
  > API methods
  > Common utility method
  > PATCH API methods
  > PUT API methods
  Test classes
  > PATCH TC1
  > POST TC1
  > PUT TC1
  Driver package
  > PATCH driver class
  > POST driver class
  > PUT driver class
  
4 The text execution is driven by Static driver class.

5 This project is capable of saving the execution evidence into text files which contains details of sent request, statuscode and response received 