# Welcome...View at your own risk!

### I'm __Julie Kwok__. 
#### Contact me at *kwokster10@hotmail.com*
#### My digits: well you should have the guts to ask me for them. 


##### I love furry animals but dogs trump them all. My new background from exploring [Bored Panda](http://www.boredpanda.com/).

![Siberian Husky on Frozen Lake](http://static.boredpanda.com/blog/wp-content/uploads/2015/03/siberian-husky-frozen-lake-dog-photos-fox-grom-15.jpg)

##### Still don't agree? Click to this video!
<a href="https://www.youtube.com/watch?v=pVudbTK0Q4o" target="_blank"><img src="http://i.imgur.com/XdcUi.gif" 
alt="French Bulldog Puppy" width="240" height="180" border="10" /></a>

##### As you can see this is dangerous and can go on all day so let's move on to other things.

```javascript
//So this is from the last exercise of the fundamentals. 
//I think I did it right but have a feeling that using .map function would have made my code cleaner. 
//Any thoughts?

function clearBoard() {
    for (var i=0; i<checkerboard.length; i += 1) {
        var h=0;
        while (h<checkerboard.length) {
            checkerboard[i][h] = null;
            h+=1;
        }
    }
}

function setUpRed() {
    for (var i=0; i<3; i += 1) {
        var h=0;
        if (i%2===0) {
            for (h=0; h<checkerboard.length; h+=2)
            checkerboard[i][h] ='R';
        } else {
            for (h=1; h<checkerboard.length; h+=2)
            checkerboard[i][h] ='R';
        }
    }
}


function setUpBlack() {
    for (var i=5; i<checkerboard.length; i += 1) {
        var h=0;
        if (i%2===0) {
            for (h=0; h<checkerboard.length; h+=2)
            checkerboard[i][h] ='B';
        } else {
            for (h=1; h<checkerboard.length; h+=2)
            checkerboard[i][h] ='B';
        }
    }
}

var pieces = {
    "red" : [],
    "black" : []
};

function piecesRed() {
    for (var i=0; i<checkerboard.length; i+=1) {
        for (var h=0; h<checkerboard.length; h+=1) {
            if (checkerboard[i][h] ==='R') {
                    pieces["red"].push([i,h]);
            }
        }
    }
}

function piecesBlack() {
    for (var i=0; i<checkerboard.length; i+=1) {
        for (var h=0; h<checkerboard.length; h+=1) {
            if (checkerboard[i][h] ==='B') {
                pieces["black"].push([i,h]);
            }
        }
    }
}
```


##### Well I'm sure you've had enough of me. Head back to the master lemon repo here:
[Lemon Github](https://github.com/ga-students/lemon.git)
