# Calcuate Tax Function
Here are the [UK tax bands](https://www.gov.uk/income-tax-rates) for 2021 as described by the UK tax authority:

Taxable Income | Tax Rate
---------------|--------:
£0 to £12,500  | 0%
£12,501 to £50,000  | 20%
£50,001 to £150,000  | 40%
over £150,000  | 45%

Given the taxable income amount, write a function called `calculateUkTax` 
that returns the tax amount given the taxable income.  The calculation 
should be based on the above table.  

Sample code,

```js
// Write the calculateUkTax function here...
...
...

let rahulTaxAmt = calculateUkTax(10000);
console.log(rahulTaxAmt); // Should print 0

let borisTaxAmt = calculateUkTax(12600);
console.log(borisTaxAmt); // Should print 20

let rishiTaxAmt = calculateUkTax(180000);
console.log(rishiTaxAmt); // Should print 61000

```

[Here is the link for the video explaination for the above problem](https://mclarencollege.com/player.html?videoUrl=https%3A%2F%2Fmclaren-college-lecture-recordings.s3.us-east-2.amazonaws.com%2Fin-class_videos%2FJavascript_Foundations%2Fuk%2Btax%2Bband%2Bproblem.mp4)

