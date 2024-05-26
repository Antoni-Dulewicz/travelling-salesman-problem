<font size="6">
Solving TSP (Traveling-Salesman-Problem) using simulated anealing algorithm:
</font>

<br>
What is simulated annealing?


CLICK HERE TO FIND OUT -> <a href="annealing.md" style="color: orange;text-decoration: underline;">SIMULATED ANEALING</a>

<br>

REAL LIFE USE CASE OF TSP -> <a href="europe_trip.md" style="color: orange;text-decoration: underline;">EUROPE TRIP</a>


<br>
We will consider 3 types of generating points:
<br>
<font size="3">
<ol>
<li>Using random.uniform() function</li>
<li>Using random.multivariate_normal() function</li>
<li>Randomly generating points in 9 clusters</li>
</ol> 
</font>
<br>

Energy function is defined as the total distance of the route. The algorithm will try to minimize this energy function.

Multiple highs and lows in the energy and temperature plot are due to the reheat functionality. 

<br>
<font size="5">

**Using random.uniform() function:**
</font>
<font size="3">

This is the energy plot for the solution:

![energy](images_for_md/uniform/energy_plot.png)

Temperature plot for the solution:

![temperature](images_for_md//uniform/temparature_plot.png)

Final solution:

![solution](images_for_md/uniform/gif_output.gif)

</font>

<font size="5">

**Using random.multivariate_normal function:**
</font>

<font size="3">
 This is the energy plot for the solution:

![energy](images_for_md/normal/energy_plot.png)

Temperature plot for the solution:

![temperature](images_for_md/normal/temparature_plot.png)

Final solution:

![solution](images_for_md/normal/gif_output.gif)

</font>

<font size="5">

**Randomly generating points in 9 clusters**
</font>

<font size="3">
 This is the energy plot for the solution:

![energy](images_for_md/clusters/energy_plot.png)

Temperature plot for the solution:

![temperature](images_for_md/clusters/temparature_plot.png)

Final solution:

![solution](images_for_md/clusters/gif_output.gif)

</font>
