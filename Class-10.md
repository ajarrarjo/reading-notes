**Error Handling & Debugging**


![err](https://www.google.com/imgres?imgurl=https%3A%2F%2Fjaxenter.com%2Fwp-content%2Fuploads%2F2017%2F08%2Fshutterstock_528370405.jpg&imgrefurl=https%3A%2F%2Fjaxenter.com%2Fnode-js-errors-changes-coming-136664.html&tbnid=yEFpoMUi3326vM&vet=10CBcQxiAoCGoXChMIkOyi9MuD7wIVAAAAAB0AAAAAEAY..i&docid=Vz_MGY4H5BPwMM&w=5000&h=4673&itg=1&q=%20UNDERSTANDING%20ERRORS%20javascript&ved=0CBcQxiAoCGoXChMIkOyi9MuD7wIVAAAAAB0AAAAAEAY#imgrc=yEFpoMUi3326vM&imgdii=oZrdAo5qaAib-M)

JavaScript can be hard to learn and everyone makes
mistakes when writing it. This chapter will help you learn
how to find the errors in your code. It will also teach you how
to write scripts that deal with potential errors gracefully.

![error](https://www.valentinog.com/blog/static/199d49f6c5443ce3336c96cf4e2395f8/ee604/error-handling-javascript.png)

|![ver](https://developers.google.com/web/tools/chrome-devtools/console/images/logviolation.png)

> Order of Execution

* The Callstack
* The Event Loop
* The Task Queue
* WebAPIs/External Resources

![order](https://miro.medium.com/max/789/1*oKvUA7QwUmks79nxkelY6g.png)

Execution context in JavaScript is of three types as:
* Global execution context (GEC)
* Functional execution context (FEC)
* Eval

![context](https://miro.medium.com/max/1542/1*y8oX0ddZ8vXcOnRIM2yjzw.png)


![err](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Errors.jpg)


**ERROR OBJECTS**

Error objects can help you find where your mistakes are and browsers have tools to help you read them.

>Error types

**EvalError**
Creates an instance representing an error that occurs regarding the global function eval().

**RangeError**
Creates an instance representing an error that occurs when a numeric variable or parameter is outside of its valid range.

**ReferenceError**
Creates an instance representing an error that occurs when de-referencing an invalid reference.

**SyntaxError**
Creates an instance representing a syntax error.

**TypeError**
Creates an instance representing an error that occurs when a variable or parameter is not of a valid type.

**URIError**
Creates an instance representing an error that occurs when encodeURI() or decodeURI() are passed invalid parameters.

**AggregateError**
Creates an instance representing several errors wrapped in a single error when multiple errors need to be reported by an operation, for example by Promise.any().

**InternalError** 
Creates an instance representing an error that occurs when an internal error in the JavaScript engine is thrown. E.g. "too much recursion".

***There are many types of errors in JavaScript, namely:***

**Error**

**EvalError**

**InternalError**

**RangeError**

**ReferenceError**

**SyntaxError**

**TypeError**

**URIError**


![Chroom](https://javascript.info/article/debugging-chrome/chrome-sources-debugger-pause.svg)

![firefox](https://www.inmotionhosting.com/support/wp-content/uploads/2013/02/website_how-to_diagnose-error-console_javascript-problems-3-firefox-javascript-console.gif)

![rakpoints](https://javascript.info/article/debugging-chrome/chrome-sources-breakpoint.svg)

**JavaScript Common Errors**

1. Uncaught TypeError: Cannot read property
2. TypeError: ‘undefined’ is not an object (evaluating
3. TypeError: null is not an object (evaluating
4. (unknown): Script error
5. TypeError: Object doesn’t support property
6. TypeError: ‘undefined’ is not a function
7. Uncaught RangeError
8. TypeError: Cannot read property ‘length’
9. Uncaught TypeError: Cannot set property
10. ReferenceError: event is not defined


![JS](https://res.cloudinary.com/practicaldev/image/fetch/s--M9YBKSmH--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/9c120odozpobnbzun791.jpg)

