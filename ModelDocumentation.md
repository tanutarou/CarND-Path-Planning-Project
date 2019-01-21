## run along the lane
Running along the lane is basic selection in my path plannning.
* I used Frenet coordinates to plan path. It is very useful to asign path.
* I used [spline library](https://kluge.in-chemnitz.de/opensource/spline/) to smooth my path. It makes that car's jerk do not exceed max jerk.
* My car's reference velocity is changed to reference velocity gradually. 

## Avoid collision
* If my car approaches other car(30m), my car's velocity will be down gradually. This algorithm makes the car can avoid collision.

## Lane change
* If my car approaches other car, my car try to change its lane. But, it will not move soon. First, my alogrithm checks whether 
my car can chage the lane. If it's okay, my car will change the lane.
