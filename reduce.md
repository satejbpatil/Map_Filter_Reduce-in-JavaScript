**Lets see the customary approaches we often follow.**


```bash
input= [5,4,6,3,7,2,8,1,9,10];

function findSum(input){
    let sum=0;
    for (let i = 0; i < input.length; i++) {
        sum+=input[i];
    }
    return sum;
}
let sum= findSum(input);
console.log(sum);
```

```bash
input= [5,4,6,3,7,2,8,1,9,10];
function findMaxElement(input){
    let max=0;
    for (let i = 0; i < input.length; i++) {
        if(max<input[i]) max=input[i];
    }
    return max;
}
let max_element= findMaxElement(input);
console.log(max_element);
```

**Now lets see by using reduce() function**

```bash
input= [5,4,6,3,7,2,8,1,9,10];

const sum = input.reduce(function(acc,curr){
    acc+=curr;
    return acc
},0)
console.log(sum);
```



```bash
input= [5,4,6,3,7,2,8,1,9,10];

const findMaxElement = input.reduce(function(acc,curr){
    if(curr>acc) acc=curr;
    return acc
},0)
console.log(findMaxElement);
```

### Output:
![Screenshot from 2024-01-17 19-44-31](https://github.com/satejbpatil/Map_Filter_Reduce-in-JavaScript/assets/112341637/c653dbb0-099c-4123-a936-d43cd2964489)

