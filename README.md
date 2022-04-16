# Python

## Data Structure

- Array
- Hash map
- Hash set
- Queue 
- Stack
- String
- Linked List
- Tree
- Graph
- Heap

## OOP

### Inheritence(继承)

```python
class Animal:
    def __init__(self, name, age, color):
        self.name = name
        self.age = age
        self.color = color
        
    def speak(self):
        pass

class Dog(Animal):
    def __init__(self, name, age, color):
        super().__init__(name, age, color)
        
    def speak(self):
        print("wong!")
        
dog1 = Dog(name="Mike", age=5, color="black")
dog1.speak()

class Cat(Animal):
    def __init__(self, name, age, color, type):
        super().__init__(name, age, color)
        self.type = type
        
    def speak(self):
        print("miu")
        
cat1 = Cat(name="mimi", age=3, color="grey", type="Curl")
cat1.speak() 
```





