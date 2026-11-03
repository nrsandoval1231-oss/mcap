# reviewer app test

Real review trigger: the function below has a genuine bug for the reviewer to catch.

```js
// TODO: this parser breaks on empty input
function parseDelimited(input) {
  return input.split(",").map((s) => s.trim())[0].toUpperCase();
}
```
