Write down your function tracing

```js
function rossy(state) {
    return (state === 4);
}

function maxwell(a, b) {
    return rossy(a) || (a > b);
}

function hammer(k, seelo, pop) {
    if (seelo) {
        return rossy(k) ? pop + k : k + pop;
    }
    else {
        return k - pop;
    }
}


let nameB = hammer('magic',  maxwell(-2, -3), 'butter');
console.log(nameB);
```
[Here is an example](https://gist.github.com/McLarenCollege/9e6732bf9483b05fcbab36ab309e6238) of a function trace we discussed earlier
