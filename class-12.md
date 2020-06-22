
# LOCAL STORGE :  

`Local Storage` : 
is a type of web storage that allows JavaScript sites and apps to store and access data right in the browser with no expiration date. This means the data stored in the browser will persist even after the browser window has been closed.

`localStorage` in JavaScript: How to To use `localStorage` in your web applications, there are five methods to choose from:
1. `setItem()` :  Add key and value to `Local Storage`.
2.  `get Item()` : Retrive a value by the key from `local storage`.
3.   `removeItem()` : remove an item by key from local storage 
4.     `clear()` :  Clear all `localStorage`.
5.     `key()` : Passed a number to retrieve nth key of a `local storage`.

**localStorage can only store strings.**


There are two types of storage you can use:
 
 1. Local storage: Data that persists even if you refresh the page or close the browser.
 2. Session storage: Data that will get cleared when the browser is closed.

You can store arrays and objects, but you have to turn them into strings first, using a method called `JSON.stringify()` and `JSON.parse()`.
