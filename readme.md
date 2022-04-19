# Recaptcha Testing
### Installation and Local deployment
1. `npm i`

2. `npx nodemon app.js`

3. locate `localhost:3000` on your browser

### How to tick the box programatically via Javascript
1. Locate the checkbox `document.getElementsByClassName('recaptcha-checkbox')`

2. Select the first matching document `document.getElementsByClassName('recaptcha-checkbox')[0]`

3. Trigger the click command `.click`

i.e. `document.getElementsByClassName('recaptcha-checkbox')[0].click()`, this will trigger the checkbox

### References
1. Keys for experimental/testing recaptcha v2
```
Site key: 6LeIxAcTAAAAAJcZVRqyHh71UMIEGNQ_MXjiZKhI
Secret key: 6LeIxAcTAAAAAGG-vFI1TnRWxMZNFuojJ4WifJWe
```

2. [Tutorial link](https://codeforgeek.com/google-recaptcha-node-js-tutorial/)

3. [Recaptcha v2 link](https://developers.google.com/recaptcha/docs/faq#id-like-to-run-automated-tests-with-recaptcha.-what-should-i-do)
