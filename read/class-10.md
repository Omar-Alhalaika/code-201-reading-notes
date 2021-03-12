# JS Debugging

>Errors, bugs, and therefore debugging are a part of life for a programmer. As the saying goes, if you haven’t made any mistakes, then you aren’t trying hard enough.

Dealing with errors actually involves two very different processes: error handling and debugging. Error handling is a combination of coding and methodology that allows your program to anticipate user and other errors. It allows you to create a robust program. Error handling does not involve weeding out bugs and glitches in your source code, although some of the error handling techniques covered in this chapter can be used to great advantage at the debugging stage. In general, error handling should be part of your overall program plan, so that when you have an error-free script, nothing is going to bring it to a screeching halt. With some sturdy error handling in place, your program should be able to keep running despite all the misuse that your users can—and certainly will—throw at it.


#Debugging
> on the other hand, involves finding errors and removing them from your program. There are many types of errors that you can unwittingly build into your scripts, and finding them provides hours of fun for all the family. Errors can result from:

* Including language features or syntax that the scripting engine does not support within the script.

* Failing to correctly implement the intent of the program or some particular algorithm. This occurs when, although code is syntactically correct and does not generate any errors, it produces behavior or results other than those you intend.

* Including components that contain bugs themselves. In this case, the problem lies with a particular component, rather than with your script, which “glues” the components together.


Debugging
You’ve designed your solution and written the code. You start to load it into the browser with high hopes and excitement, only to be faced with an big ugly gray box telling you that the VBScript engine doesn’t like what you’ve done. So where do you start? Well, I find that another cup of coffee helps, but most of the time the error’s still there when I rerun the script.

When confronted with a problem, you first need to know the type of error you’re looking for. Bugs come in two main flavors:

Syntax errors
You may have spelled something incorrectly or made some other typographical or syntactical error. When this happens, usually the program won’t run at all.

Logical errors
Although syntactically correct, your program either doesn’t function as you expect, or it generates an error message.

Bugs appear at different times, too:

At compile time
If a compile-time error is encountered, an error message appears as the page is loading. This usually is the result of a syntax error.

At runtime
The script loads OK, but the program runs with unexpected results or fails when executing a particular function or subroutine. This can be the result of a syntax error that goes undetected at compile time or of a logical error.

Let’s look at each type of bug individually. We’ll begin by looking at syntax errors, first at compile time and then at runtime, before looking at logical errors.

Syntax Errors
