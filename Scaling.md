# Scaling
Scaling a **load balancer** lets you adjust its performance to its workload by changing the number of nodes the load balancer contains. You can scale load balancers up or down at any time to meet your traffic needs. You can scale a load balancer to adjust its performance to its workload. Scaling changes the number of nodes the load balancer contains. **You can scale load balancers up or down at any time to meet your traffic needs.**

If you are running a website, web service, or application, its success hinges on the network traffic it receives. It is common to underestimate how much traffic your system will incur, especially in the early stages. They could result in a crashed server and a decline in your service quality.

But what options do you have for implementing scaling and ensuring your business's scalability? That's where horizontal and vertical scaling come in.

# Horizontal Scaling

Horizontal scaling refers to adding additional `nodes` or machines to your `infrastructure` to cope with new demands. If you are hosting an application on a server and find that it no longer has the capacity or capabilities to handle traffic, adding a server may be your solution.

The horizontal scaling of one node that is damaged will not affect the whole server.

![This is an image](https://virtualfeller.com/wp-content/uploads/2020/01/horizontal-load-balancing.png)

# Vertical Scaling

Vertical scaling describes adding additional resources to a system for it meets demand. 
While horizontal scaling refers to adding additional nodes, vertical scaling describes adding more power to your current machines. For instance, the server requires more processing power, this vertical scaling would mean upgrading the CPUs. You can also vertically scale the memory, storage, or network speed.

![This is an image](https://virtualfeller.files.wordpress.com/2020/01/vertical-load-balancing.png)

# Horizontal Vs. Vertical Scaling

Once again, the main functional difference between the two is that horizontal scaling often forces you to rework how you implement your services or layers.
![This is an image](https://www.cloudzero.com/hubfs/blog/horizontal-vs-vertical-scaling.webp)

In the case of horizontal scaling, we can delegate each tier to a different node. However, you may already be running these tiers on variety of servers but find that one of these servers is underperforming or no longer meets demands. Once again, you can choose to scale this server vertically or horizontally. You may upgrade it with more resources or add another server to share the workload.

# Advantages of horizontal scaling

     1. Horizontal scaling is low cost when compared with vertical scaling.
     2. Easier to run fault tolerance.
     3. Ability to scale out as much as possible.
     4. Horizontal scaling is high availability.

# Disadvantages of horizontal scaling

     1. Software has to handle all the data distribution and parallel processing complexity.
     2. Higher utilization of electricity.

# Advantages of vertical scaling

     1. Most of the software can easily take advantage of vertical scaling. Because it runs smoothly.
     2. Less power consumption for running multiple servers.
     3. Easy to manage and install.

# Disadvantage of vertical scaling

     1. It requires a more amount of financial investment.
     2. Greater risk of hardware failure.
     3. Vendor lock-in and limited upgradeability in features.
     4. vertical scaling is low availability.

# References

     . This site provided information[CloudZero](https://www.cloudzero.com/blog/horizontal-vs-vertical-scaling)
     . Refering this video[2.1 Scaling in Cloud Computing](https://youtu.be/Mt-782k-Zck)
     . This site provided information[virtualfeller](https://virtualfeller.com/vertical-or-horizontal-load-balancing/)
