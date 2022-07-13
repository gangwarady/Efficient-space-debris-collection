# Efficient-space-debris-collection

For more than a decade, the Space Debris problem has become a major problem for space researchers. As of data of 2019, there are about 900,000 pieces of debris of size between 1 and 10 cm and there are more than 128 million debris of size less than 1 cm traveling at the rate of 20 times the speed of the bullet.

With the growing space sector of countries, the space environment is becoming crowded. The major problem is when these space items are used up then also they remain in the orbit which is called space debris. This space debris can be collided with the satellites incurring heavy losses to upcoming space programs.

The method used for debris removal is Active Debris Removal (ADR) which involves a parent satellite with some small satellites in it. Whenever the parent satellite detects debris then it releases the sub satellites from it which can trap the debris using different deorbit devices equipped in them and move the debris to lower orbit.

The issue here is to deal with a plan that can take these sub satellites efficiently to all the identified debris in the range with the minimization of energy (fuel) and the time. This problem can be modeled as a traveling salesman problem.

The satellite system consists of many sub satellites which can be considered as many salesmans and the debris that they have to collect can be considered as cities after deorbiting the debris the main satellite moves to other debris and once removing all debris have to come to the space depot like International space station. Also when the propellant or the spacecraft carried by the main satellite is insufficient, it is necessary for the main satellite to return to the space depot for replenishment. So the exact problem can be solved as a Multiple Traveling Salesman Problem.

The above steps can be summarized as follows : 
1. The main satellite moves to the debris. 
2. Sub satellites are released from the main satellite. 
3. Sub satellites take the debris to the lower orbit. 
4. The main satellite can now move to the next debris. So the main focus is now solving this Multiple Traveling Salesman Problem. Multiple algorithms can be used to solve such Multiple Traveling Salesman Problems.
