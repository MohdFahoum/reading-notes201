### LOCAL STORAGE

localStorage is a type of web storage that allows JavaScript sites and apps to store and access data right in the browser with no expiration date.
This means the data stored in the browser will persist even after the browser window has been closed.


![link](https://techglimpse.com/wp-content/uploads/2013/05/Pass-LocalStorage-data-to-PHP-using-jQuery.jpeg)


localStorage in JavaScript: 
How to To use localStorage in your web applications, there are five methods to choose from:

setItem(): Add key and value to localStorage
getItem(): Retrieve a value by the key from localStorage
removeItem(): Remove an item by key from localStorage
clear(): Clear all localStorage
key(): Passed a number to retrieve nth key of a localStorage

*setItem()
Just as the name implies, this method allows you to store values in the localStorage object.
It takes two parameters: a key and a value. The key can be referenced later to fetch the value attached to it.

*getItem()
The getItem() method allows you to access the data stored in the browser’s localStorage object.
It accepts only one parameter which is the key and returns the value as a string.

*removeItem()
When passed a key name, the removeItem() method will remove that key from the storage if it exists.
If there is no item associated with the given key, this method will do nothing.

*clear()
This method, when invoked, clears the entire storage of all records for that domain. It does not receive any parameters.

*key()
The key() method comes in handy in situations where you need to loop through keys and allows you to pass a number or index to localStorage to retrieve the name of the key.



####Browser support
localStorage as a type of web storage is an HTML5 specification.
It is supported by major browsers including IE8. To be sure the browser supports localStorage.


localStorage limitations
As easy as it is to use localStorage, it is also easy to misuse it. The following are limitations, and also ways to NOT use localStorage:

Do not store sensitive user information in localStorage
It is not a substitute for a server based database as information is only stored on the browser
localStorage is limited to 5MB across all major browsers
localStorage is quite insecure as it has no form of data protection and can be accessed by any code on your web page
localStorage is synchronous, meaning each operation called would only execute one after the other



