5-25-2021 DAILY JOURNAL
https://ericwakeman.github.io/gregslist/

# Three states of promise, how do they solve callback hell, difference between then() and catch()?

Pending, resolved, rejected. Promises allow chaining of callback functions to run sequentially and allow to error check all the callbacks with one piece of code rather than writing catch for each callback. Then() is the action taken if the promise resolves, catch() is the action taken if the promise is rejected.