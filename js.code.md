1. Write the function which give the following result
```javascrpt
spacify('hello world') // => 'h e l l o  w o r l d'
```

2. put the function on the string object
```javascrpt
'hello world'.spacify();
```

3. Difference between function statement and function expressions
   

4. Define a log function which could proxify console.log
```javascript
log('hello world')
```

5. Define a log function which could accept one or more arguments
```javascript
log('hello', 'world');
```

6. Define a log function which could accept one or more arguments and prefix it by (app)
```javascript
'(app) hello world'
```

7. What is the output of the following code
```javascript
var User = {
  count: 1,

  getCount: function() {
    return this.count;
  }
};

console.log(User.getCount());

var func = User.getCount;
console.log(func());
```

8. what is the output of the following code 
```javascript
var a = {n:1};
var b = a;
a.x = a = {n:2};

alert(a.x);
alert(b.x);
```

9. remove duplicated elements from array


10. difference between shallow copy and deep copy, and write a deep clone function


11. write a function that returns a random integer between min (include) and max (include)