### Scaling: Horizontal vs Vertical Scaling
## What is scaling?
In system Design term scaling is the process increase system's performance and resource to handle more traffic or load without making it more complex.
##### There is two types of scaling:
- [[#Vertical Scaling]] (Scaling-up)
- [[#Horizontal Scaling]] (Scaling-out)
### Vertical Scaling:
Vertical scaling is also know as scaling-up, the process of increasing the system capacity or capabilities of a existing hardware or software component within a system. You can add more power to your system by adding better processor, increasing RAM or making other changes. Vertical scaling aims to improve the performance and capacity of system without changing fundamental architecture or adding additional servers.

![[vertical_scaling.png]]
##### Pros of Vertical Scaling:
- Ease Management
- Consistence
- Increase Capacity

##### Cons of Vertical scaling:
- Limited scalability
- Single point of failure
- Increase cost
### Horizontal Scaling:
Horizontal scaling also know as scaling-out, the process of increase the capacity or performance of a system by adding more machines or servers to distribute the workload across all nodes or unit. 

In horizontal scaling no need to change or replace the server we simply add more and more servers or machine to handle more requests.
![[Pasted image 20240707235006.png]]

##### Pros of Horizontal Scaling:
- Increase capacity
- Improve performance
- Increase fault tolerance
##### Cons of Horizontal Scaling:
 - Complexity
 - Data inconsistency 
 - Increase cost
