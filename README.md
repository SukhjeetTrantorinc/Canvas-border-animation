# Canvas-border-animation
A simple canvas border animation using Javascript - not complete see issue

DrawX() holds the main animation while setInterval(drawX,5) creates the rectangle repetition. Each rectangle starts at a position using drawRec(). DrawX() also starts the first rectangle at the bottom, then it uses an if(){} to transition to the next rectangle moving up on the right, drawY()...

```javascript
function drawX(){//bottom/left move right}
function drawY(){//bottom/right move up}
function drawXT(){//top/right move left}
function drawYL(){//top/left move down}

setInterval(drawX,5)

function drawRecX(){//bottom left}
function drawRecXtR(){//top right x}
function drawRecY(){//top left y}
function drawRecYbR(){//bottom right y}
```

