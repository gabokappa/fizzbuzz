## FizzBuzz Exercise ##

This is an initial pair-programming exercise carried out together with another student in my Makers Academy cohort.

# Aim
The goal of Fizzbuzz is to introduce you to Test Driven Development (TDD) and Pair Programming.

# Instructions

If you want to follow this exercise, you can find a version of this on this blog post: [An introduction to TDD in Ruby](https://blog.makersacademy.com/an-introduction-to-tdd-in-ruby-72f0a8536509)

A word of warning, in the blog post there is an error under the section:
# Writing the first test

The example code in the describe test section should read as follows (Note: the 'it' on the first line should go on the second line. )

```shell
describe 'fizzbuzz' do
 it 'returns "fizz" when passed 3' do
   expect(fizzbuzz(3)).to eq 'fizz'
 end
end
```
