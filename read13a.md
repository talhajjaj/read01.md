**Local Storage;**

 Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data, but it have many issues ;

1. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over.

2. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL).

3. Cookies are limited to about 4 KB of data enough to slow down your application , but not enough to be terribly useful.


and what we want is having alot of space in our storage ,
HTML5 Storage” is a specification named web storage, it was a part of the HTML5 specifiction proper, its named as local storage or DOM storage , so the storage it’s a way for web pages to store named key/value pairs locally, within the client web browser.

You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats,  If you are storing and restore anything other than strings, you will need to use functions like parseInt() or parseFloat().  

so we use these functions in HTML to  treat the local storage;
 Calling **setItem()** with a named key that already exists will silently overwrite the previous value. Calling **getItem() **with a non-existent key will return null rather than throw an exception.
 There are also methods for removing the value for a given named key, and clearing the entire storage area,Calling **removeItem()**.

 The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something,The storage event is supported everywhere the localStorage object is supported.

 and for sure you should know these keys ;

 **Storage event objects:**

- key	string;	the named key that was added, removed, or modified.

- oldValue;	any	the previous value (now overwritten), or null if a new item was added.
- newValue;	any	the new value, or null if an item was removed.

- url;	string	the page which called a method that triggered this change.