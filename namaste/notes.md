https://www.youtube.com/watch?v=iLWTnMzWtj4&list=PLlasXeu85E9cQ32gLCvAvr9vNaUccPVNP&index=3

# execution context

## memory (variable environment)
variables and functions as key/value pairs
key: value
a: 10
fn : { ... }

## code component (thread of execution)
- code executed one line at a time
-

syncronous, single-thrreaded language
one at a time, in order
ajax? async





var n = 2;
function square (num) {
  var ans = num * num;
  return ans;
}





1st phase
memory creation phase

js allocates memory
a spatial value, undefined

n: undefined

fn square: {
  the whole fn code here in memory
}

2nd phase
code execution phase
n: 2 value is put into member

function invocation
  square(n)


  memory component
  code component

a new  execution context

  memory creation phase



---
# call stack
global execution context

maintains the order of execution

aka
Call Stack
execution context stack
program stack
control stack
machine stack
runtime stack


