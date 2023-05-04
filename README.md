# EM_Planner
This is an autonomous vehicle's planning algorithm. This algorithm is based on APOLLO emplanner, based on sampling.

转自 [忠厚老实的老王](https://GitHub.com/VincentWong3)
## Chapter 1: Foundations of Mathematics
### Section 1: Polynomial Blends (五次多项式)
Jerk\,\,=\,\,\frac{da}{dt}\,\,a: acceleration
\\
\text{质点的轨迹} s\,\,=\,\,f\left( t \right) \,\,\Rightarrow Jerk\,\,=\,\,\frac{d^3f}{dt^3}\,\,\left[ 0, T \right] 
\\
find\,\,f\left( t \right) . s.t. \min \int{\left( \frac{d^3f}{dt^3} \right)}^2\mathrm{dt}
\\
![plot](./EM_Note/EMPlanner_01.png)
