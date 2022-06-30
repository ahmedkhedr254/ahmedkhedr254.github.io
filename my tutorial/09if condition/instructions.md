#if condition

```dart
main(){
    int x= 5;
    if (x<10){  
      print("here inside if");
    
    }
}
```
     
##else if   and else if  and else example
    
```dart
main(){
    int degree= 76;
    if (degree<=85){  
          print("excellent");
    }
    else if(degree<85&&degree >=75){
      print("very good");
    }
    else if(degree<75&&degree >=65){
      print("good");
    }
    else if (degree<65&&degree >=60){
      print('passed');
    }
    else {
          print('failed');
    }
}
```

##nested if
```dart
main(){
int x=44;
  if (x<80&&x>20){
    if (x>70){
      print("here from nested");
    }
  }
  else {
    print("here outside");
  }
}
```
