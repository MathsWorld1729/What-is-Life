## What is Life?
This is surely a debatable question so we will break it up in different sections. 

### Equation of Life
$$Life=\int_{Birth}^{Death} \frac{Happiness(time)}{time} \, d(time)$$

**Explanation:** The idea here is happiness is a function of time and it varies person to person and evetually changes according his behaviour in life. $Happiness(time) \in \mathbb{R}$ and $time \geq 0$ as usual. Time in the denominator says if $H(t) >0$ then when time increases over all happiness has a external decreasing effect it is due to time, whereas if $H(t)<0$ then as time increases due to that time again overall sadness decreases.\\
Here $H(t)>0 \implies Happiness(time)$ and $H(t)<0 \implies sadness(time)$. Now finally we integrate all the resulting momentary emotions(either happiness/sadness) and get the total net outcome of life.

**Note:** This equation may be improved, we can make it optimised for an optimal life. May be denominator is a function of time which is increasing and positive. Many things is on the fly but one important thing to fix is that during birth $time=0$, so the function above is not defined and also integral near zero may not be convergent, so refine the above integral as,
$$Life=\int_{Birth+\delta}^{Death} \frac{Happiness(time)}{time} \, d(time), \, \delta >0$$

We have to now, figure out wheter the following inegral is convergent or not,
$$Life=\int_{Birth}^{Birth+\delta} \frac{Happiness(time)}{time} \, d(time), \, \delta>0$$
For example if $H(t)=t^{p} ,\, p>0.$ Then the above integral converges and life begins. Which is usual as we born happiness increases with time as $p>0$ but if $p\leq 0$ or in other words happiness decreasing then life doesn't exists and then to keep the integral value finite limits has to be equal or in other words $Birth=Death$.