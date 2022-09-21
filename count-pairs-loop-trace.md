# Count Pairs

Guess the output of the following code by writing a loop trace.

Note: Do not include the variable `nums` in the loop trace since its value never changes.


```js
function countPairs(nums) {
    let left = 0;
    let count = 0;
    while (left < nums.length) {
        let right = left + 1;
        while (right < nums.length) {
            if (nums[left] + nums[right] === 100) {
                count++;
            }
            right++;
        }
        left++;
    }
    return count;

}
console.log(countPairs([70, 30, 70]));
```
