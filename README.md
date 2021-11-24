![alt text](https://github.com/Mahmoudms994/vue-photo/blob/main/unnamed.jpg)
# What is vue.js?

 Vue is also perfectly capable of powering sophisticated Single-Page Applications when used in combination with modern tooling and supporting libraries.
 
 What do you need to start:
 
  intermediate level knowledge of HTML, CSS, and JavaScript. If you are totally new to frontend development

# vue.js requiers:


1-download node.js from here : https://nodejs.org/en/download/.


## on cmd open documents and then:

2- download vue.js latest version : 
 ```
 npm install vue
```

3- download vue.js latest version :
```
npm install vue-cli -g
```

4- download webpack latest version :  CMD:
```
npm install --save-dev webpack
```

 or specific version
 ```
 npm install --save-dev webpack@<version>
 ```
 
5- download vue devtools extiention for chrome:  
https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd
    
 # What to do first?
  
  the simplest example : hello world
  1-cmd in documents/vue
  ```
  code index.html
  ```
  
  2-copy the code to the index.html page in vs.code:
  ```
  <!DOCTYPE html>
<html>
<head>
  <title>My first Vue app</title>
  <script src="https://unpkg.com/vue"></script>
</head>
<body>
  <div id="app">
    {{ message }}
  </div>

  <script>
    var app = new Vue({
      el: '#app',
      data: {
        message: 'Hello Vue!'
      }
    })
  </script>
</body>
</html>
```
#### or copy it from 
  https://codesandbox.io/s/github/vuejs/vuejs.org/tree/master/src/v2/examples/vue-20-hello-world?file=/index.html

  
  

  



