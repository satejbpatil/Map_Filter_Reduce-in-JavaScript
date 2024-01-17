**Lets see the customary approaches we often follow.**


```bash
input= [5,4,6,3,7,2,8,1,9,10];

output=[];
function greaterThan5(input){
    for (let i = 0; i < input.length; i++) {
        if(input[i]>5 ) output.push(input[i]);
    }
}
greaterThan5(input);
console.log(output);
```

**Now lets see by using filter() function**

```bash
input= [5,4,6,3,7,2,8,1,9,10];

const output = input.filter((x) => x>5 )
console.log(output);
```

### Output:
![Screenshot from 2024-01-17 17-39-56](https://github.com/satejbpatil/Map_Filter_Reduce-in-JavaScript/assets/112341637/083d5a80-7b63-45c9-b3a2-1370d828f59d)
