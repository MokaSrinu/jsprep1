
# Js Prep-1
 
 ## Topics
 <ol>
 <li>Data types</li>
 <li>Arithmetic Operators</li>
 <li>Comparision Operators</li>
 <li>Logical Operators</li>
 <li>Conditional Statements</li>
 <li>Functions,arguments,return statement,scope</li>
 <li>callback,higherOrder functions</li>
 <li>forloops,while,do-while</li>
 <li>Arrays</li>
 <li>Objects</li>
 </ol>

 # 1) Data Types:

    1.a)Primitive DataTypes
        -The data that is not an object and has no properties or methods like non Primitive data types(like arrays,functions)
        -These are the basic building blocks of the program.(being the first in existance.)
        -They hold the actual value(By value)

       There exists 5 Primitive DataTypes:
          1)String:
              JavaScript's String type is used to represent textual data. It is a set of "elements" of 16-bit unsigned 
              integer values. Each element in the String occupies a position in the String. The first element is at 
              index 0, the next at index 1, and so on. The length of a String is the number of elements in it.

          2)Boolean:
              Boolean represents a logical entity and can have two values: true and false.

          3)Number:
              ECMAScript has two built-in numeric types: Number and BigInt — along with the related value NaN.
              -The Number type is a double-precision 64-bit binary format IEEE 754 value. It is capable 
                of storing positive floating-point numbers between 2^-1074 (Number.MIN_VALUE) and 2^1024 
                (Number.MAX_VALUE) as well as negative floating-point numbers between -(2^-1074) and -(2^1024), 
                but it can only safely store integers in the range -(2^53 − 1) (Number.MIN_SAFE_INTEGER) to 2^53 − 1 
                (Number.MAX_SAFE_INTEGER).     
              -The BigInt type is a numeric primitive in JavaScript that can represent integers with arbitrary precision. 
               With BigInts, you can safely store and operate on large integers even beyond the safe integer limit for Numbers.     

               ## Example:          
                         // BigInt
                         > const x = BigInt(Number.MAX_SAFE_INTEGER);
                         9007199254740991n
                         > x + 1n === x + 2n; // 9007199254740992n === 9007199254740993n
                         false

                         // Number
                         > Number.MAX_SAFE_INTEGER + 1 === Number.MAX_SAFE_INTEGER + 2; // 9007199254740992 === 9007199254740992
                         true

          4)Undefined:
                A variable that has not been assigned a value has the value undefined.

          5)Null:
                The value null represents the intentional absence of any object value. It is one of JavaScript's primitive 
                values and is treated as falsy for boolean operations.                   
    
    1.b)NoN-Primitive data Types:
        There exists 3 non primitive. They are:
           1)Object  : Collection of key,value pair.
           2)Array   : Storing multiple values as long list.
           3)Function: Executes a block of code.   

  # 2) Arithmetic Operators:        