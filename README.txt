Ans 1 - 

(a) x = max(1,2,3)
While our parser will not be able to handle more than 2 arguments in the max function and will throw an error, the Python compiler can handle 
this easily.

We can extend the compiler to support multiple arguments by supporting a ... function in the grammar that specifies arbitrary arguments.

(b) 1 - (2 - 3)
Our compiler is does not support parenthesis priority and will thus evaluate this to -4 (left priority). Python's compiler outputs 2.

We can extend the grammar of the compiler to support parenthesis.

(c) max(1, **arrayVals), where arrayVals is a tuple that can be unpacked. Python will unpack arrayVals and pass it to max, while our compiler will
run into parsing errors.

To solve this, we need to significantly extend our grammar and make it as sophisticated as Python's

Ans 2 - 
The WASM docs and the Javascript tutorial were extremely useful. While the Typescript tutorial was useful, at the end the Javascript tutorials helped
a lot more for determining the syntax of the code.

Ans 3 - 
I worked solo on my assignment. However, I did code along during Yousef's office hours for a majority of the assignment.