#boolean expression
any boolean expression return true or false
##comparison operation
 ### < less than
 ### <= less than or equal
 ### > bigger than
 ### >= bigger than or equal
 ### == equal
 ### != not equal

```dart
main (){
  print(3<10);
  print(10<3);
  print(3<=3);
  print(10>=3);
  print(10==3);
  print(10!=2);

}
```

##Boolean Operators
boolean operations get two boolean expressions and return boolean expression
### and operation &&
|x  |y  |x&&y|
|---|---|---|
|true|true|true|
|true|false|false|
|true|true|false|
|true|false|false|

### or operation ||

|x  |y  | x or y |
|---|---|---|
|true|true|true|
|true|false|true|
|false|true|true|
|false|false|false|

### negation operation ||

| x  |!x |
|---|---|
|true|false|
|false|true|

```dart
int z=20;
int y=30;
int z=20;
print(x>y&&x==y||x>=z&&z==x);
print(z!=y&&x>=z);
print(!x<z);
print(!x>=y);
```
##using brackets () 
you can use brackets so the expression inside brackets execute first and it make expression more readable

int z=20;
int y=30;
int z=20;
print((x>y)&&x==y||(x>=z||y<z)&&z==x);

```