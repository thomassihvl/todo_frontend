# Expass 6

## Part 1
Part 1 went very well. The steps in the tutorial worked and i created a Model-View-Controller app.

## Part 2
This part became much larger than expected.

I started with squashing some small bugs and refamiliarizing myself with the code from the experiment 4 that we were supposed to use as backend. After all the Postman requests were successfull I started taking a look on Angular. I took some time installing node etc. and started following this [Angular tutorial](https://angular.io/tutorial/).

The tutorial was much larger than expected and I had to make a lot of adjustments to make it fit with my backend. The main problem was CORS configuration, Angular and Spark did not play very well without the proper CORS configurations, which I had no idea how to set up. After a lot of trying, testing and failing I got the headers right, set some options in Spark and set up a proxy in Angular to bypass the CORS problems. I'm pretty sure the only thing that actually did something was the SPARK settings. 

I did not bother with part 3 as I used a lot of time on part 2.

## Summary
I created a SPA using Spark API and even with a little bit too much overhead, the application was successfull in the end.



[Todo app frontend](https://github.com/thomassihvl/todo_frontend)

[Todo app backend](https://github.com/thomassihvl/dat250-sparkjava-counter)