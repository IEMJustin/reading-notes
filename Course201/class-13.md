# Local Storage

The type of way to store data was different back then. <br>
Cookies were invented but they had A LOT of drawbacks such as unencrypted data being sent or the slowing down of applications. <br>
There were other attempts to create a viable source to store data but none were viable. <br>

This was until HTML5 came along and changed the whole game. <br>
HTML5 Storage will store named key/value pairs locally, within the web client browser. <br>
The data stored is never transmitted to the remote web servers unless the user decides to manually send out the data. <br>

The data that gets stored is based on a named key that can be retrieved with the same key.<br>
The functions parseInt() or parseFloat() will need to be utilized if the data stored is anything that is not a string. <br>
Calling setItem() will overwrite the previous value. <br>

## Reference
- http://diveinto.html5doctor.com/storage.html