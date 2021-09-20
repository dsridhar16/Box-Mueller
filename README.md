# Box-Mueller
We are asked to get 260 normally distributed values for the stock portfolio, which we can do using the Box-Muller method. 
After that, we just need to calculate the stock value based on the previous day. Then we plot the stock values according to the day. 
The first thing we do is plot the current stock value to the day. Then, we will randomly generate two numbers between 0 and 1. 
After that we will apply the Box-Muller transformation on those two random numbers and we have our normally distributed stock change for the next day. 
After this, we calculate how much the stock changes and what it will be for the next day. 
We do this for 260 days and each time, you plot the stock value to its proper day. 
In some cases, the stock value with a performance fee was higher than the one without a performance fee. Just to make sure these were aberrations, 
I made another while loop that ran each method 1,000 times. 
I then summed all the 1,000 results up to make sure that in the long run, the stock value with no performance fee was higher than the one with a performance fee. 
This checked out so I am confident in my result. I had to comment this part out but if you would like to verify it, make sure to comment out 
the plotting of the points. Otherwise, you will end up getting 1,000 different graphs. 

