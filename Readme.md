"Bye world! 2" 

it's the string you wish to check for the presence of a number in the code above.
you can test it with this script:

```
hasNumber(input) {
  return /\d/.test(input);
}
```
Any digit between 0 and 9 matches the regular phrase /\d/.
If there is a match in the string, the regular expression object's .test() method returns true; otherwise, it returns false.
