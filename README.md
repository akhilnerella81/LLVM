# LLVM
## C++11/C++14 FEATURES:

* Final keyword:  
     Its a C++11 feature.This keyword is used in Macroargs.h,It is used for preventing inheritance of class.  
     When a class/struct is marked as final then it cant be inherited and cant be used as baseclass.  
     Reference: https://github.com/llvm/llvm-project/blob/main/clang/include/clang/Lex/MacroArgs.h

* delete:  
     This is also a C++ 11 feature used in LLVM.Before C++ 11 the delete operator can only be used to deallocate memory.In the new feature it can also disable usage of a member function.  
     This feature is used : https://github.com/llvm/llvm-project/blob/main/clang/include/clang/Lex/HeaderMap.h

* Explicit keyword:  
 This feature is used to avoid implicit conversions we make constructor explicit using explicit keyword.  
 This feature is used in : https://github.com/llvm/llvm-project/blob/main/clang/include/clang/Lex/MacroInfo.h
     
* nullptr :  
 C++ 11 nullptr replaces C's NULL.nullptr is implicitly convertible and comparable to any pointer type unlike null.
      https://github.com/llvm-mirror/clang/blob/master/include/clang/Lex/HeaderSearch.h
* Unique_ptr :  
 Its a smart pointer if it goes out of scope deletes the object pointing to.  
 Reference:https://github.com/llvm-mirror/clang/blob/master/include/clang/Lex/HeaderMap.h
* Inline Namespace:
  Ref: https://github.com/llvm-mirror/clang/blob/master/include/clang/Lex/HeaderSearchOptions.h
* Noexcept -   noexcept specifier tells whether a function could throw exceptions.Improved version of throw().     
* Template -
  This feature is used : https://github.com/llvm/llvm-project/blob/main/clang/include/clang/Lex/MacroInfo.h
* constexpr :  
 Constant expression are evaluated by compiler at compiletime.Only non-complex computation are done here.We use this to indicate variable/function.
 Reference: https://github.com/llvm-mirror/clang/blob/master/include/clang/ASTMatchers/ASTMatchersInternal.h
* std::move -  
 Object passed to it transfers resources.  
 https://github.com/llvm/llvm-project/blob/main/clang/lib/Frontend/ASTUnit.cpp		
* Non-static data member initialiser:  
 It allows nonstatic datamembers to initialise when declared for cleaning up constructors. 	
* auto :  
 Auto variables are deduced by compiler acc. to type of which it is assigned.  
      https://github.com/llvm/llvm-project/blob/main/clang/lib/Frontend/ASTUnit.cpp
* default :  
 Provides a default implementation of a function.
      https://github.com/llvm-mirror/clang/blob/master/include/clang/Lex/Pragma.h
* using  :  
 Similar to typedef in "C".
      https://github.com/llvm-mirror/clang/blob/master/include/clang/Lex/HeaderSearch.h
* Rangebased for loop -  
 For iterating over a rrange in a containerCompilerInvocation.cpp.  
   Reference:https://github.com/llvm/llvm-project/blob/main/clang/lib/Frontend/CompilerInvocation.cpp
* Static_assert -  
 To check if a condition is true when code is compiled else issues an error.  
 Reference:https://github.com/llvm-mirror/clang/blob/master/include/clang/ASTMatchers/ASTMatchersInternal.h

## Class Hierarchy

Reference:https://github.com/llvm/llvmproject/blob/main/clang/include/clang/Analysis/PathDiagnostic.h
![image here](a.jpeg)  
The above chart is of Hierarchical Inheritance of llvm:FoldingsetNode class.This is the base class and more than one derived class is created from single base class.

