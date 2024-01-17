

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

**Now lets see by using map() function**

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

### Output:
![Screenshot from 2024-01-17 17-28-54](https://github.com/satejbpatil/Map_Filter_Reduce-in-JavaScript/assets/112341637/4fe840f2-b4fd-4dcb-ac1e-d2b535afde96)


