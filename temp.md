**Answer**:

> _"1. Consider, for example, if you were working for Bay Area Bike Share..."_

1.1. Do our users use the bike to **commute to work**?

  *  It could be worth to know if the users take the bike regularly to go to work. If we find out that there is a high number of users using the service with this purpose, we **could create offers, discounts, partnerships or agreements with companies** within an area or neighbourhood.  

  * Suppositions / Simplifications / Assumptions
    * We will assume that we want to focus on **"office work"**. This means Monday to Friday from 08:00 to 17:00
    * We have a ``user_ID`` so we can track if "user1" travels from A to B and from B to A within the same day
    * We will focus in **subscribers** since they will be the ones that might use this service _(it would be so expensive for no subscribers)_


  * To reach this goal we could analyse:  
    * Trip weekday (Mo-Fr)
    * Trip start hour (between 07:00 and 09:00)
    * Trip start hour (between 16:00 and 18:00)
    * Trip End Station (in the hours of interest)
    * Subscription type
    * Check if there are approximately the same number of trip from A to B in the morning than from B to A in the afternoon
    * Trip End station could be crossed with a companies directory where we could analyse which companies are located near the bike stations.


1.2. Once a user takes a bike in station A, **could we predict** where he/she will **leave the bike**?

  * If a certain user takes the bike to commute to work from station A to station B every monday to friday, but on Tuesdays he has a, for example, a tennis class near station C,
    we could predict (with certain margin of error) where he/she will leave the bike


1.3. Where should we open more stations/terminals?

   * If we find out that we are running out of stock in some stations we might **open new stations** in the **most requested areas**.
   * Similarity, we could predict **where and when we will need more bike stock**. For example, if a high percentage of users take the bike to go to the stadium X when the team Y plays.

1.4. Are the users **driving directly** from station A to station B or is there something else in between?

  * Let´s say from station A to station B are 3 Km and it takes users in average 10 minutes
  * We could track those users/trips that are **way far from the average**, for example, those tripts that took more than 30 minutes (3 times the average)
    * Had they a **technical issue** with the bike?
    * Did they **stop** somewhere to buy/meet friends?

1.5. How do users behave when they drive at night?

-----------------------

> _"2. What factors might influence how you would want to use the service?"_

2.1. _"I want to use the bike to make a long route with a couple of friends"_

  * Is there any bonus/gift if I bring new users?
  * I am not sure if these bikes are suitable for the route I am planning, it would be nice if the company can offer more than one bike model (like a mountainbike).
  * This leads to the question: _"Are our users **riding alone** or **with a friend** at their side?"_
    * There might be business cases where two or more friends use the service to do a (long) route.
    * The company might consider, for example:
      * **rewarding users** if they bring new users, or
      * offering some kind of discount (**pay one get two** or **pay two get three**)
      * **placing mountainbikes** in some locations if we find a trend

2.3. _"I am out of fit, and my city is pretty wavy, there are many hills and ramps"_

  * However I would like to use it to go to work because I don´t have a car and the public transport is more expensive.
  * It would be great if they add a electril engine in the bikes
  * This leads to the question: _"**How many customer** could we **attract** if we add an **engine** in our bikes"_
    * Through surveys in the cities with uneven profile we could analyse if this is profitable
