# Functions

### Exercise 1

```javascript
var myName = 'Go4Tech';

var sayMyName = function(name) {
    return "Hello " + name;
}
sayMyName(myName);
```

### Exercise 2

a.

```javascript
var snake = GAME.createSnake();
```

b.

```javascript
var snake = GAME.createSnake(myName, "green");
```

```javascript
var snake = GAME.createSnake(myName, "green");
GAME.draw(snake);
```

### Exercise 3

a.

```javascript
var moveSnake = function(direction){
    GAME.setDirectionForSnake(direction);
}
```

b.

```javascript
var moveSnake = function(direction){
    GAME.setDirectionForSnake(direction);
    GAME.move();
}

moveSnake('right');
moveSnake('down');
```