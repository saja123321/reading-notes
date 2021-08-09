#  LOCAL STORAGE FOR WEB APPLICATIONS

The numbers in the table specify the first browser version that fully supports Web Storage.

|      API           |            Web Storage       |
|--------------------|------------------------------|
|       IE           |         8.0+                 |
|	FIREFOX	         |         	3.5+                |
|    SAFARI          |         	4.0+                |
|    CHROME          |          4.0+                |
|    OPERA	         |      	10.5+               |
|    IPHONE          |          2.0+                |
|	ANDROI           |       	2.0+                |



in `js` file the function below added to HTML to `detect whether the browser supports it.` 

```
function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}
```

## STORAGEEVENT OBJECT



|      PROPERTY         |	TYPE	   |       DESCRIPTION                                             |
|-----------------------|--------------|---------------------------------------------------------------|
|          key	        |    string	   |     the named key that was added, removed, or modified        |
|oldValue	            |  any         |   the previous value  or null if a new item was added         |
|  newValue             |	any	       |     the new value, or null if an item was removed             |
|      url*	            |   string     |	the page which called a method that triggered this change  |


------------------------------

# USING HTML5 STORAGE

Storege the data in HTML5 as `key/value pairs`  the data stored in the `key` name and the `value`geting by the  same `key` 

> the data is stored as a `string` , but we can change the datatype by `parseInt()` or `parseFloat()`.

to remove item we use  `removeItem(`key_name`)`

wethout the `key_name` it not remove any thing.
-----------------------------------

#### to get the total number of values in the storage area 
```
interface Storage {
  readonly attribute unsigned long length;
  getter DOMString key(in unsigned long index);
};
```