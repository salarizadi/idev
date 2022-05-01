# iDev

Browser console opening detection


> Import :

`<script src="idev.js"></script>`

> Instructions :

`iDev.listener(function (opened) {
  document.querySelector(".status").innerHTML = (opened ? "Opened" : "Closed");
});`

`document.querySelector(".ismobile").innerHTML  = "Mobile  : " + (iDev.mobile ? "true" : "false");`
`document.querySelector(".iswindows").innerHTML = "Windows : " + (iDev.windows ? "true" : "false");`
`document.querySelector(".ismac").innerHTML     = "Mac : " + (iDev.mac ? "true" : "false");`

`iDev.run();`
