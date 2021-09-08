# assignment2-pattela-

Hi this is Rithesh Reddy
# Pattela Rithesh kumar reddy 
## My favourite place in the world is goa 
<br> I am fond of **beaches** from childhood and **goa** is place which is famous for it's beaches. That's the reason i liked goa very much.
***
# Route MAP from Maryville to Goa
1. Take a cab to kansas city airport
2. Take flight from kansas to dallas
3. Take again a flight from dallas to newyork.
4. Travel to goa by using below route 
   1. book a flight from newyork to manchester international airport
   2. from manchester to dabolim airport 
   3. travel 30km to reach panjim which is state capital.
5. finally reached destination 

* carry enough money .
* keep your luggage and documents safely.
* plan your stay before you reach the destination like hotels
  * Hardrock hotel
  * Mayfair hotel
  * Baywatch hotel
* Food

---

[About me](https://github.com/S545258/assignment2-pattela/blob/main/Aboutme.md)

![My picture](/Rithesh.jpg?w=true)

# FoodAndDrinks
  The Following Table illustrates the Best food and drinks available in different locations near me at the best price.<br> Please refer to this table and choose what you want.

   | Food/Drink  | Location    | Price |
   | ----------  | --------    | ----- |
   |  Biryani    | kurry leaves|  12$  |
   |   Burger    | McDonalds   |  1$ |
   |chickenwings | mooyah      |  8$   |
   |   Nuggets   | Taco Bell   |  2$   |

---

# Pithy Quotes
> Everything is easy when you are busy. But nothing is easy when you are lazy.
                                                                      *-Swami Vivekananda*
                                                                         
> Talk to yourself atleast once in a Day.. Otherwise you may miss a meeting with an EXCELLENT person in this World.
                                                                                                           *-Swami Vivekananda*

---

# String Processing 
> we can detect if there is a negative cycle in our graph. We know that, to find out the shortest path, we need to relax all the edges of the graph (V-1) times, where V is the number of vertices in a graph. We have already seen that in this example, after (V-1) iterations, we can't update d[], no matter how many iterations we do. Or can we?

If there is a negative cycle in a graph, even after (V-1) iterations, we can update d[]. This happens because for every iteration, traversing through the negative cycle always decreases the cost of the shortest path. 
[Source](https://riptutorial.com/algorithm/example/24034/detecting-negative-cycle-in-a-graph)

```
for (int i = 0; i < n; ++i) {
    for (int j = 0; j < n; ++j) {
        for (int t = 0; t < n; ++t) {
            if (d[i][t] < INF && d[t][t] < 0 && d[t][j] < INF)
                d[i][j] = - INF; 
        }
    }
}
```
[Source](https://cp-algorithms.com/graph/finding-negative-cycle-in-graph.html)




