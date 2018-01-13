Welcome to the PUSHJS-Notification- wiki!

https://www.youtube.com/watch?v=HY1SZTY8hVc

* npm install push.js --save

`<!DOCTYPE html>`
`<html>`
`<head>`
    `<title>Realtime Notifications</title>`
    `</head>`
    `<body>`
  `<button id="btn">PUSH nOTIFICATION</button>`
`<script type="js/Push.min.js"></script>`
`<script>`
`var btn=document.getElementById('btn');`
`btn.addEventListenet('click',function(){`
`Push.create("hello htihs",{`
`body:"tutorial",`
`icon:"https://ps.com/images/crododile.jpg".`
`timeout:4000,`
`onClick:function()`
`{`
`this.close();`
`}`
`});`
`});`
`</script>`
`</body>`
`</html>`
