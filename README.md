# Tua
Tua is a superset of lua with typing,enums and better memory management(with pointers)
## Hello World
this is the tua hello world
```lua
str:hello = "Hello World!"
print(hello)
```
this is the tua hello world(with pointers)
```lua
str:hello = "Hello World!"
str*:ptr = hello@
print(hello)
free(ptr)
```
## build targets
1. LUA
2. Javascript(don't know yet)
## TAKE&takepkg
take: build system
takepkg: package manager(builds with take)
## Special features
True and False now have the values of 1 and 0 respectively
```lua
TUA 1.0.0 - (based off of lua54 by PUC-Rio)
> x = true + true
2
> x = false + false
0
> x = false + true
1
```
## dreamberd
