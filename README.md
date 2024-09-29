# js-dev-environment
Java script development environment

##### Content of the program
1. Introduction of ecma script EC6
2. Language enhancement
3. Array and collection enhancement
4. Asynchronous programming
5. Advanced Techniques
##### ref: firtman.github.io/projs
1. Brenden Eich created JavaScript in 1995
2. JS 1.0 to becomes ECMA Script(ES1) in 1997
3. ES3 was released on 1999
4. ES5 was released on 2009
5. ES6 started in 2015
##### how define private field in java Script
``` we use # as prefix for private variable or private methods while declaring the variable or function within the class```
##### for example: 
```
    class MyDeclarationProperties(){
    this.#FirstName = "vlaue of first name
    #continateFirstnameAndLastName(){
        this.#FullName = this.#firstName +this.#seconName;
    }
}
```
##### Its also supports static variable and static method and static block
```
Class Person{
    static{
...
...
    }
    static age = 24;
    static listAll(){

    }
}
this block will get execute only once when the class get intantiated.
```

##### we can regular expression in JavaSript as below
```
const text = 'cchckkk 2004-04-20'
const reguleEx= /\b(\d{4})-(\d{2})-(\d{2})\b/g;
for(const [fullDaye , year , month, date] of reguleEx){
    console.log($fullDaye);
    console.log($year +"-"+ $month + "-" + $date)

    }
```

