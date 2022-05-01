# iDev

Browser console opening detection


> Import :

```
<script src="idev.js"></script>
```

> Instructions :

```
iDev.listener(function (opened) {
  document.querySelector(".status").innerHTML = (opened ? "Opened" : "Closed");
});

document.querySelector(".ismobile").innerHTML  = "Mobile  : " + (iDev.mobile ? "true" : "false");
document.querySelector(".iswindows").innerHTML = "Windows : " + (iDev.windows ? "true" : "false");
document.querySelector(".ismac").innerHTML     = "Mac : " + (iDev.mac ? "true" : "false");

iDev.run();
```

> See all features :

`See this value in your browser console before calling the iDev.run() method`
`See more commands and features`

```
console.log(iDev)
```

> Support Browser :

- Chrome
- Firefox
- Safari
- Edge
- Opera
- IE9+ (need Promise polyfill)
