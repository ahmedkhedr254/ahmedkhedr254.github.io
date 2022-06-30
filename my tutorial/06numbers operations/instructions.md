#06 numbers Operations

##addition operation +
```dart
main(){
    int x=20;
    int y=30;
    print(x+y);
    
    double x=20.2;
    double y=30.4;
    print(x+y);
}
```

##subtraction operation -
```dart
main(){
    int x=20;
    int y=30;
    print(x-y);
    
    double x=20.2;
    double y=30.4;
    print(x-y);
}
```

##multiplication operation *
```dart
main(){
    int x=20;
    int y=30;
    print(x*y);
    
    double x=20.2;
    double y=30.4;
    print(x*y);
}
```

##division operation /
```dart
main(){
    int x=50;
    int y=5;
    print(x/y);
    // division result in decimal and  cant assign the result of division to int
    int z=x/y; ==>error
    
    double z=x/y;

}
```
##modulus operation %
 ## y = a*x + r 
```dart
main(){
    print(50%2);
    print(11%2);
    

}
```


##integer value can be assigned in double variable
```dart
main(){
    int x=40;
    double y=x;

}
```


##double value can't be assigned in int variable
```dart
main(){
    double x=40;
    double y=x;

}
```
##conver double and int to string using [toString()]
```dart
main(){
    double x=40;
    int y=x;
    String z=x.toString()+" "+y.toString();
}
```
##conver String to int and double
```dart
main(){
    String s1=200;
    int x1=int.parse(s);
    double y1=double.parse(s);
    print(x1);
    print(y1);

    String s2=200.0;
    double y2=double.parse(s);
    print(x1);
    
    //this string cant be parsed to int and it will throw formatExcebtion
}
```
##decimal methods
###round() method : used to round decimal to the nerest int
###toInt() method : used to remove decimal part
###floor() method : used to get nerest upper int to the decimal
###ceil() method : used to get nerest lower int to the decimal
```dart
    void main(){
         double x=20.4;
         print(x.toInt());
         print(x.round());
         print(x.floor());
         print(x.ceil());
    }
```