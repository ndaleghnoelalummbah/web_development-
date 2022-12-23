# web_development

This repo is for html, css and javascript
This is an end project excercise after a two weeks training with shecodes

### The Challenge was to build any simple landing page making use of html tags,css styles and javascript

###screenshots

![screen capture](./images/capture.png)

###some codes on javascript which I used

```function purchase() {
        let name = prompt("please enter your name");
        let email = prompt("please enter your email");
        if (name.trim() != 0 && email.trim() != 0 && (email.endsWith("@gmail.com") == 1 || email.endsWith("yahoo.com") == 1) && email.startsWith("@gmail.com") == 0 && email.startsWith("yahoo.com") == 0) alert(`Dear ${name}, an electronic receipt will be sent to ${email} right after the purchase.`);
        else alert("Please identify your self");
      }

      let button = document.querySelector("button");
      button.addEventListener("click", purchase);
```
