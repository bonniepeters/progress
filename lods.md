# Code Log

### July 13, Monday

**Accomplishments:**
1. Finished the [Square(n) Sum](https://www.codewars.com/kata/515e271a311df0350d00000f/javascript) on Codewars.

<details><summary>Code</summary>
<p> Sum of Digits/Digital Root

```javascript
function squareSum(numbers){
  let squared = numbers.map(num => num * num);
  let total = 0
  for (i = 0; i < squared.length; i++) {
    total += squared[i];
  }
  return total;
}
```

</p>
</details>
