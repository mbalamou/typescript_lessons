### 1.4 Generics/type programming

- Generics
	- Why is it better than any?
	- Use cases (useState<>, Component<>)
	- Create `map` using generics

### Exercises

1. Create a generic function called `filter` that takes an array and a function and returns a new filtered array.

Example: 
    
```ts
filter([1, 2, 3, 4], (element) => element % 2 === 0)  
// returns [2, 4]

filter([‘hello’, ‘world’, ‘cat’, ‘dog’, ‘cat’], (element) => element === ‘cat’)  
// returns [‘cat’, ‘cat’]
```