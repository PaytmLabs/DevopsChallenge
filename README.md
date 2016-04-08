
Devops Challenge: 

Answer the following with as much detail as you are comfortable, and email your answers to the contact who pointed you here.

- You are free to assume any technique/technology you think relevant can be used to solve the given problem.
- State all assumptions in describing your solution

Q1: You have been given 1000 nodes to bootstrap, install hadoop/elasticsearch/cassandra (whatever distributed software you're
familiar with) and test/check. assume all 1000 nodes have been wired etc. How would you go about it?

Q2: How would you go about installing OS on these nodes ? How much time would it take ? (what if we had 10000 nodes)

Q3: How would you implement a system that distributes a file to 1000 nodes ? (Any changes if 10000 nodes ?)

Q4: How would you prevent unauthorized access to the cluster resources ? (Assume cluster service does not have intrinsic authentication / authorization built in)

Q5: You have configured Namenode HA. One day when the active NN down, you notice standby NN did not take over. What may cause it? How would you investigate what has happened?  If you see both NN are in standby mode, how to fix it?

Q6: You have turned on SQL Standard-Based Authorization for Hive. user 'joe' is allowed to run select on table 'audit'; meanwhile, user 'joe' has no access permission to the HDFS folder holding the data for table 'audit'. If Joe execute "select * from audit", what he will get?

Q7: You have configured capacity scheduler queues for you Yarn cluster. One day you found one queue resource is fully occupied by a huge job launched by user 'joe' while lots of other users' jobs are pending. How do you prevent it happening?  
