#11 switch
Example 
```dart
void main() { 
   var grade = "A"; 
   switch(grade) { 
      case "A": {  print("Excellent"); } 
      break; 
     
      case "B": {  print("Good"); } 
      break; 
     
      case "C": {  print("Fair"); } 
      break; 
     
      case "D": {  print("Poor"); } 
      break; 
     
      default: { print("Invalid choice"); } 
      break;
   }
}  
```

##break
int the following example the first case will not break after satisfy the condition
and the third case also will be execute
```dart
void main() { 
   int x = 74; 
   switch(x) { 
      case 74:print("1th case");
      
      case 40:print("2th case");
      break; 
     
      case 74:print("3th case");
      break; 
     
      case 30:print("4th case"); 
      break; 
     
      default:  print("Invalid choice"); 
      
   }
}  

```