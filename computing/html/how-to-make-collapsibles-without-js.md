You can make collapsibles without needing to code any JavaScript.
You just need the `<details>` tag and a `<summary>` to be the text that is displayed before the user actually clicks the arrow.

Code:

```
<details>
  <summary>What is this thing?</summary>
  <p>
    Ruby is an expressive, versatile, and flexible dynamic programming language. That means there are all kinds of syntax features, operators, and symbols we can encounter that might look unfamiliar and are hard to look up. Ruby Operator Lookup is a directory of all these language features.
  </p>
  <p>
    Use the search bar to narrow down the results. Then click on a button for the operator or symbol you want to explore further.
  </p>
</details>
```

It will be displayed, at least at first, as a white triangle rotated before the text that you put in the `summary` tag.

result: 

<details open>
  <summary>What is this thing?</summary>
  <p>
    Ruby is an expressive, versatile, and flexible dynamic programming language. That means there are all kinds of syntax features, operators, and symbols we can encounter that might look unfamiliar and are hard to look up. Ruby Operator Lookup is a directory of all these language features.
  </p>
  <p>
    Use the search bar to narrow down the results. Then click on a button for the operator or symbol you want to explore further.
  </p>
</details>
