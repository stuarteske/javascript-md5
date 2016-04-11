# javascript-md5
Complete encapsulated Javascript MD5 library.

## Dependances
None.  

## Usage
Include the script in the footer of the body HTML.  
```<script src="/js/libs/md5/md5.js"></script>``` 
  
Call the MD5 function and assign the result to a variable for later use.  
```var myMd5HashedString = MD5("my super secret password");```

Always salt the MD5 function if possible.  
```var salt = "some-random-text";```  
```var myMd5HashedString = MD5(salt + "my super secret password");```
