# LLVM
## C++11/C++14 FEATURES:

* Final keyword:
      Its a C++11 feature.This keyword is used in Macroargs.h,It is used for preventing inheritance of class.
      When a class/struct is marked as final then it cant be inherited and cant be used as baseclass.
      Reference: https://github.com/llvm/llvm-project/blob/main/clang/include/clang/Lex/MacroArgs.h

* delete:
      This is also a C++ 11 feature used in LLVM.Before C++ 11 the delete operator can only be used to deallocate
      memory.In the new feature it can also disable usage of a member function.
      This feature is used : https://github.com/llvm/llvm-project/blob/main/clang/include/clang/Lex/MacroInfo.h

* Explicit keyword:
      This feature is used to avoid implicit conversions we make constructor explicit using explicit keyword.
      This feature is used : https://github.com/llvm/llvm-project/blob/main/clang/include/clang/Lex/MacroInfo.h
     
* NULL ptr :
      
* Unique_ptr      https://github.com/llvm/llvm-project/blob/main/clang/include/clang/Lex/HeaderMap.h
* Noexcept
       
* Template   LLparser.h ,Macroinfo.h
* const/constexp   ASTMatchersInternal.h  
* move 
* Initialise list  		
* NSMI	
* default   pragma.h
* using  modulemap - headersearch.h
Rangebased loop -  CompilerInvocation.cpp
* Static_assert Apvalue.cpp/ASTMatchersInternal.h

##Class Hierarchy

![image here](a.jpeg)
