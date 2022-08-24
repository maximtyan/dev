# Engineering software development

I will summarize my personal notes on software development process in 
our lab. The case studies are based on multiple aircraft design, 
optimization, simulation and other projects completed during the 
past years.

# Getting started

## Computer configuration

There are several tips that can make development little bit easier.

### Make your username easy to type

Make it short, use small letters, avoid using spaces or special symbols.

My username on any PC is **maxim** (5 symbols, no capital 
letters, no spaces, no special symbols).

You will probably have to type your username in a terminal quite often. Keeping it simple will save some time and your little finger.

Sometimes you need to type a directory path in a terminal. Some 
terminals require quotes if the path contains space. 

```
cd ./username/
cd "./user name/"
```

Removing space from path name will save you some more time. 

The same advice can be applied to any directory, file name, name of 
your project and other names you will have to type often.

### Source code directory

I recommend to keep all your development projects closer to disc root. 
It will simplify navigation and allow to avoid errors with old programs.

I keep my development projects at:

```
D:\src
```

Some old analysis programs often used in engineering have limitations 
for the length of file path. For example XFOIL and AVL will not run if 
the path length is longer than 40 symbols. 

AVL cannot open this file:
```
D:\my-study\classes\aircraft-design\design-code\avl-input-file.txt
```

But it will open this

```
D:\src\design-code\avl-inp.txt
```

## Git

[how to setup git](https://maximtyan.github.io/dev/git_setup)


## Python

- IDE
- venv
