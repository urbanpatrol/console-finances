# Weekly Challenge 4

## Console Finances

## Contents
* [Description](#description)
* [Approach](#approach)
* [Challenges](#challenges)


## Description

It was requested to utilise Javascipt to calculate the various financial queries from a given dataset. 

## Links
You can find the link to the index.html page where you will open developer tools in your preferred browser to view the results in the Console [Console Finances](https://urbanpatrol.github.io/console-finances/index.html)

## Approach
Apart from class learnings, considerable research was required to complete the tasks. Searches online revealed all manner of results but I chose to keep the approach in line with what we have learned rather than adopting new code or functions not yet learned. Not to say that my knowledge base is any lesser as a result as it has been broadened merely through research.

For this task, the index.html and index.js files were already provided with the 'finances' array.

## Challenges
#### *Pseudo Code*
Pseudo coding is a really good way of thinking out a problem and found this approach handy. However, there were some areas that still gave me difficulty and I have an answer to query 3 that is different to that provided. My formula is below:

>* The average of the **changes** in Profit/Losses over the entire period.
>* You will need to track what the total change in profits are from month to month and then find the average.
>* (`Total/Number of months`)

>var totalChange = 0;

>for (var i = 1; i < finances.length; i++) {
    totalChange += finances[i][1] - finances[i - 1][1];
>}
>console.log(totalChange) // = -196785

>average = totalChange / finances.length;

>console.log(Math.round(average));
>console.log(average.toFixed(2));

>= -2288.20

## Credits

* StackOverflow many times over and Google.

## License

MIT

## Features

n/a

## Tests

n/a

---

© 2022 Ramon Fritz. Confidential and Proprietary. All Rights Reserved.