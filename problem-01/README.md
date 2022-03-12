# Problem #01

https://projecteuler.net/problem=1

If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.

Find the sum of all the multiples of 3 or 5 below 1000.

## Notes

- create a slice to store results
  - or keep a sum counter while looping
- loop over all the numbers from 0 - 1000
- create a slice of numbers below 1000 that have 0 remainder on modules 3 or 5

```go

var sum int

for i = 0; i <10; i++ {
  if i % 3 {
    sum += i
  }
  if i %5 {
    sum += i
  }
}

```

## Solution

233168
