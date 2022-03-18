# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

** SUMMARY **
The function takes the input of *animal* , makes all the characters in the string lowercase, and checks if it is "alligator" . If it is "alligator" the function returns *small* -- if it's anything else, the function returns *wide* . 

```js
function (animal){
  const normalizedName = animal.toLowerCase()

  if (normalizedName === "alligator"){
    return "small"
  } else {
    return "wide"
  }
}
```

| Input     | Output    |
| --------- | --------- |
| ALLIGATOR | small     | 
| Crocodile | wide      | 
| Alligator | small     | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program insults alligators by calling them small.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
