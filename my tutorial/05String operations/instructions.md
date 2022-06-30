#05 String Operations

```dart
main(){
//assign string with '

String s1='ahmed';

//assign string with "

String s2="mohamed";
}
```

##scape operation \
scape operation used to add special characters like (",',\) in string to be able to print it

```dart
main(){
//add ' character to string created with '

String s1='ahmed\'';
print(s1);

//add " character to string created with "

String s2="mohamed\"";
print(s1);

String s3="ahmed\\";
print(s2);

String s3="ahmed\$";
print(s2);

}
```
##string concatination +
used to concatenate two string
```dart
main(){
//add ' character to string created with '

String s1='ahmed';
String s2="mohamed";
print(s1+s2);
print(s1+" "+s2);

//int and double must be converted to string before concatenate
int x=5;
String ss="ahmed age is "+x;  //==>error
}
```

```dart
main(){
//int and double must be converted to string before concatenate
int age=25;
String ss="ahmed age is "+x.toString(0);
}
```

## string interpolate
###use $ to get variable value inside string
```dart
main(){

int age=25;
String year='year';
String s1='ahmed age is $age $year';

}
```

###use ${} to get variable and variable properties
```dart
main(){

String  myString="my string";
String year='year';
String s='my string length is : ${myString.length}';
print(s);
}
```

###substring
In this example, we will take a String and find the substring of it defined by starting index and ending index.

```dart
void main(){
     
    String str = 'HelloTutorialfordart';
     
    int startIndex = 0;
    int endIndex = 5;
     
    //find substring
    String result = str.substring(startIndex, endIndex);
     
    print(result);
}

```