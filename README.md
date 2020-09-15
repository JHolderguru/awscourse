### This is a solutions Architect Certification

#### Prerequisite
#### AWS fundamentals

### EC2 Instances
#### Reserved instances is timed and cheaper than on-demand

#### Request Spot instance- unused capacity for less, but when some one wants to use it they pay a higher price i.e large computing jobs doing batch(make sure you save your work)

#### Saving plans - like a containers service, Savings Plans are a flexible pricing model that offer low prices on EC2, Fargate and Lambda usage, in exchange for a commitment to a consistent amount of usage (measured in $/hour) for a 1 or 3 year term. Savings Plans provide you the flexibility to use the compute option that best suits your needs and automatically save money, all without having to perform exchanges or modifications

#### Dedicated host - dedicated for your use - not sharing underlaying hardware just dedicated to you. An Amazon EC2 Dedicated host is a physical server with EC2 instance capacity dedicated for your use and allows you to reliably launch EC2 instances on the same Dedicated host over time.
#### Scheduled Instances - Scheduled Instances allow you to reserve Amazon EC2 instances on a recurring Schedule. You can purchase daily, weekly, or monthly reservations to ensure your applications have the compute capacity you need, when you need it.

#### Capacity Reservations - Capacity Reservation requests are granted or denied based on your EC2 instance limits and our available capacity. When you create a Capacity Reservation, we reserve the specified capacity for your use. The reserved capacity is charged at the selected instance type’s On-Demand rate whether an instance is running in it or not. You can also use your regional reserved instances with your Capacity Reservations to benefit from billing discounts.


## Public, Private and Elastic IP addresses

#### Lost when the instance is stopped
#### Used in Public Subnets, No charge, Associated with a private IP address on the instance, Cannot be moved between instances.
## Private IP address
#### Retained when the instance is stopped Used in Public and Private Subnets.
## Elastic IP address.
#### Static Public IP address.
#### You are charged if not used.
#### Associated with a private IP address on the instance.
#### Can be moved between instances and Elastic Network Adapters.
