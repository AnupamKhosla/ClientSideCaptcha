## ClientSideCaptcha

Pure Client side js captcha(Unsecure!), Demo: http://anupamkhosla.github.io/ClientSideCaptcha

Build on top of gist https://gist.github.com/SneakyBrian/5209271 written by Sneaky Brian  

# API Example:  

```
var captcha = new $.Captcha({ //initialize captcha  
    selector: "#captcha",  
    text: null,  
    randomText: true,  
    randomColours: true,  
    width: 244,  
    height: 163,  
    colour1: null,  
    colour2: null,  
    font: 'normal 40px "Comic Sans MS", cursive, sans-serif',  
    onFailure: function() {  
       alert("Failure!");  
    },  
    onSuccess: function() {  
        alert("CORRECT!!!");  
    }  
});  
captcha.generate(); //Generate or refresh captcha
captcha.validate(); //validate filled captcha
```


`npm` support to be added soon.
