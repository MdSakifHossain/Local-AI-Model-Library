# Prompts

## Web

```txt
make me a js string reverse function with jsdoc. it will only accept string. and it will efficiently return the reversed string. think of this code will run in a super tight production environment. performance is what expected. think of this code to run in a production environment this will run for 50k to 1M times a minute also make sure that it this works with emojis and special characters. im thinking abut the less operations, less conversions. as less as it could get. think of all the edge cases carefully. also use modern js syntax
```

## Agent

````markdown
Perform this task using the available tools. Do not merely describe what you would do; actually perform each step.

1. Create a file named `agent_test.js` in the current working directory containing:    

```js
function add(a, b) {
  return a + b;
}

console.log(add(2, 3));
```

2. Read the file back and verify that its contents are correct.
    
3. Run the file using the shell.
    
4. Modify `agent_test.js` so that the function multiplies instead of adds, and change the example call to use `4` and `5`.
    

The final file should contain:

```js
function add(a, b) {
  return a * b;
}

console.log(add(4, 5));
```

5. Read the modified file back and verify it.
    
6. Run the modified file using the shell and verify that the output is `20`.
    

Do not create any other files.

At the end, briefly report whether every step succeeded.
````
