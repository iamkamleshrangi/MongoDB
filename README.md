# MongoDB
Bash script to create sharding on local machine 

# Sharding:
Sharding is a method for distributing data across multiple machines. MongoDB uses sharding to support deployments with very large data sets and high throughput operations.Database systems with large data sets or high throughput applications can challenge the capacity of a single server. For example, high query rates can exhaust the CPU capacity of the server. Working set sizes larger than the system’s RAM stress the I/O capacity of disk drives. There are two methods for addressing system growth: vertical and horizontal scaling. Vertical Scaling involves increasing the capacity of a single server, such as using a more powerful CPU, adding more RAM, or increasing the amount of storage space. Limitations in available technology may restrict a single machine from being sufficiently powerful for a given workload. Additionally, Cloud-based providers have hard ceilings based on available hardware configurations. As a result, there is a practical maximum for vertical scaling. Horizontal Scaling involves dividing the system dataset and load over multiple servers, adding additional servers to increase capacity as required. While the overall speed or capacity of a single machine may not be high, each machine handles a subset of the overall workload, potentially providing better efficiency than a single high-speed high-capacity server. Expanding the capacity of the deployment only requires adding additional servers as needed, which can be a lower overall cost than high-end hardware for a single machine. The trade off is increased complexity in infrastructure and maintenance for the deployment.

MongoDB supports horizontal scaling through sharding.

![](https://severalnines.com/sites/default/files/mongodb_cl2.png)

# Example 
 Tested On: ubuntu 16.04
 Mongodb version: 3.4

1. Auto install mongodb.
2. Create sharding on it.
3. enable sharding on test0.
4. Create shard key as test_id.

Use command 
# sudo bash mongoes.sh




