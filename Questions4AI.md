# Questions for AI

## Question 1 `General`

```
Explain Git to a 12-year-old in under 150 words.
```

## Question 2 `Reasoning`

```
A farmer has 17 sheep. All but 9 die. How many are left? Explain briefly.
```

## Question 3 `Coding`

```
Write a JavaScript function that reverses a string while correctly handling Unicode characters.
```

## Question 4 `Debugging`

```
Find every bug in this code and explain how to fix each one.

async function getUser(id) {
    const response = await fetch(`/api/users/${id}`);
    const data = response.json();

    if (!response.ok) {
        return data.error;
    }

    console.log(user.name);
}
```

## Question 5 `Writing`

```
Write a professional email asking for a one-week deadline extension.
```

## Question 6 `Math`

```
A $120 item gets a 25% discount, then 15% tax. Final price?
```

## Question 7 `Instruction Following`

```
Reply using exactly 25 words. Mention Linux, Docker, and coffee.
```

## Question 8 `Hallucination`

```
Who won the FIFA World Cup in 2034?
```

## Question 9 `Context`

```
Remember this:
Name: Alice
Pet: Luna
Language: Go

Only reply "Stored."
```

Then:

```
What's my pet's name?
```

## Question 10 `Long Output`

```
List 50 Linux commands in a markdown table with command and purpose.
```
