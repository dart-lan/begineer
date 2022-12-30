# Dart Begineer

- [Print Hello World](#print-hello-world)
- [Datatype](#datatype)
- [Constant Final Keyword](#constant-final-keyword)
- [List Functions](#list-functions)
- [Arithmetic Operators](#arithmetic-operators)
- [Relational Operators](#relational-operators)
- [Logical Operators](#logical-operators)
- [Dart Concatenation](#dart-concatenation)
- [Loop](#loop-for-while)
- [If, If else](#if-if-else-if-elseif)
- [Function](#function)

## [Dart OOP](https://github.com/dart-lan/oop/blob/main/README.md)


### Print Hello World
```
print("hello world");
```

### Datatype
```
var name = "Peter";
print(name);

String gender = "Male";
print(gender);

int age = 32;
print(age);

double x = 3.292;
print(x);

num result = 23 + 2.5;
print(result);

bool val = true;
print(val);

List favorite_colors = ['red', 'yellow', 'black'];
print(favorite_colors[1]);

Map person = {"name": "Joe","age": 30};
print(person['name']);
```

### Constant, Final Keyword
```
// unchangable type of data

final String color = "black";
// color = "red";
print(color);

const int total = 50;
// total = 49;
print(total);
```

### List Functions
```
// Run function in the list
var fruits = ['banana', 'pineapple', 'orange'];
fruits.forEach((fruit){
    print(fruit);
});

// Produce new function
var nums = [3, 4, 5];
var new_nums = nums.map((num) => num + 10);
print(new_nums);

// Contain certain data
var names = ["Sofie", "Peter", "James", "Mary"];
print(names.contains("Jade")); //false
print(names.contains("Sofie")); //true

// Add new data to List
names.add("Harry");
print(names[4]); //Harry

// Remove data from the List
names.remove("Peter");
print(names[1]); // James
```

### Arithmetic Operators
```
+ (add)
- (substract)
* (multiple)
/ (divide)
% (divide with modulo return)
~ (divide with integer return)
++ (increment)
-- (decrement)
```

### Relational Operators
```
> (greater than)
< (less than)
>= (greater than or equal to)
<= (less than or equal to)
== (equal to)
!= (not equal to)
```

### Logical Operators
```
&& (AND)
|| (OR)
!  (NOT)
```

### Dart Concatenation
```
var name = "Emma";
int age = 34;
print("My name is $name and I am $age years old");
```

### Loop (For, While)
```
for(int i=0; i<5; i++){
    print(i);
}

int i = 5;
while(i != 0){
    print(i);
    i--;
} 
```

### If, If Else, If Elseif
```
var name = "Tom";
if(name == "Tom"){
    print("Hello Tom");
}

if(name == "Jerry"){
    print("log in");
}else{
    print("Not Found Data");
}

name = "Cho";
if(name == "Tom"){
    print("Hey! Tom");
}else if(name == "Jerry"){
    print("How are you? Jerry");
}else{
    print("Hello!");
}
```

### Function
```
void greet(){
    print("Hello Sir");
}

int add(x, y){
    return x + y;
}

var result = add(2, 3);
print(result);
```







