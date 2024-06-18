# Sum of n numbers Test Package

Here is the simple function you can get from this package is

``` JavaScript
    const sumOfNums = (...res) => {
        let sum = 0;
        for (let i = 0; i < res.length; i++) {
            sum += res[i];
        }
        return sum;
    }
```



## Usage

import the method into your project using this

``` 
import sumOfNums from '@klaxe/sum-of-n-numbers'
```

now you can use the sumOfNums method which returns a sum of number which is an array

``` Javascript
 const sum = sumOfNums(5, 5, 5, 5)
 console.log(sum)
```

this will result in
``` Javascript
console
20
```


# Thank you

this package is my practise and I will produce more packages for the Developers

### About Me

I am Murali Krishna professionally known as **klaxe** and here are my socials you can check out
[LinkedIn](https://www.linkedin.com/in/murali-krishna-sake/)
[GitHub](https://github.com/Kanna116)
[npm store](https://www.npmjs.com/~klaxe)
[twitter](https://x.com/klax_e)
[Portfolio](https://klaxe-portfolio.vercel.app/)