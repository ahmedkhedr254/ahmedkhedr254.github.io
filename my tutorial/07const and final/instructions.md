#07const and final
the const and final variables can't be changer after first assignment
##what is the different between const and final ?
### the final variable can be assign in run time
### the const variable must be assign in code 
```dart
main(){
  const int x=20;
  //cant change x value
  x=22; =>error
  // cant assign another variable to const
  const z1;



}
```


```dart
main(){
  final z2;
  int y=40;
  int g=30;
  z2=y+g;
  
}
```

