

**Lets see the customary approaches we often follow.**


```bash
input= [5,4,6,3,7,2,8,1,9,10];
output=[];
function squareNum(input){
    for (let i = 0; i < input.length; i++) {
        output.push(input[i]*input[i]);
    }
}
squareNum(input);
console.log(output);
```

**Now lets see by using Map() function**

```bash
input= [5,4,6,3,7,2,8,1,9,10];

function square(x) {
    return x*x;
}

const output = input.map(square);
console.log(output);
```

OR

```bash
input= [5,4,6,3,7,2,8,1,9,10];

const output = input.map((x) => x*x);
console.log(output);
```


