cl_number- destructor 1.0
-------------------------

Side project for the next class usage- project.

The implementation of the destructor of the class cl_number.

This is important because it does a calculation (addition of the two stored numbers) and returns the result before the object is removed.

So an object of  cl_number  can be used to do an addition by creating it with two numbers to add and then removing it:

  double result;
  
  cl_number num_object (111, 222);
  
  result = delete num_object;
  
  
This sure seems not to make very much sense, but in that case some code space can be saved to also let a calculation be done.

And I wanted to include tidying up the object.
 


Version history
---------------

Version 1.0

Initial version

