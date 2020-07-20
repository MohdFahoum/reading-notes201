### DEBUGGING

Debugging is a process for testing, finding the errors and reducing them from happening in future. 
Debugging JavaScript either requires having support for JavaScript debugger keyword, breakpoint support with web browser tools, or third-party tools.

These tools range from browser plugins like Augury which is an Angular development and debugging extension for Chrome,
third-party tools & more. It is also possible to use 'debugger' keyword support (depending on the browser type and version)
and to freeze the code at a given point and investigate the issue. Let us look at few popular debugging and error handling tools.


*How to Debug JavaScript Errors
Debugging JavaScript errors in a production environment can be a difficult experience. 
More often than not, the error reports are vague, and identifying the underlying causes can be difficult at best.
That said, there are a few common steps that can be followed towards identifying and resolving errors that crop up in production.


In software development, the first step towards debugging any issue is attempting to replicate the circumstances.
With most programming languages, this is bolstered by reviewing logs leading up to an error, but with client-side JavaScript,
this type of diagnosis requires significantly more foresight (more on that below).

Before we can replicate any circumstances of an issue, and assuming we have access to any production logs,
we first need to establish some testing guidelines. This involves doing things like mimicking the production database,
the user accounts involved, and even the operating system. Everything is fair game here.


Once you've established the circumstances that you think might throw the exception or error you are hunting down,
it's time to test them. Never test exceptions in production.
Development and staging environments are designed to be breakable without any impact on the end users, so always always always try to break your code in a safe environment.

![link](https://www.guru99.com/images/asp-net/061516_0956_AspNetTraci2.png)


