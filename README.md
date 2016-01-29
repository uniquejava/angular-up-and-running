## Chapter2
第18页, controller第二个参数传数组的原因:
 The array holds all the dependencies for the controller as string variables,
  and the last argument in the array is the actual controller function. In this case, because we have no dependencies, 
  the function is the only argument in the array.
  The function then houses all the controller-specific code.