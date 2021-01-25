- reduce takes a callback function with 2 parameters....accumulator and value
- set initial value of the accumulator to 0
- value is set the first number which is 10
- accumulator is set to that value
- then value is set to the 2nd number 5 then they get added together 

    const numbers = [10, 5];
    const total = numbers.reduce((accumultor, value) => {
        return accumultor + value
    }, 0)
    console.log(total)
