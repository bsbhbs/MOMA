# MOMA
The proposed MOMA takes into account the load balancing and reliability of the cloud platform. Firstly, an intelligent task deployment framework was constructed using a multi-objective multi-agent approaches, introducing the reliability of the cloud platform as one of the multiple objectives within the framework, thereby improving the efficiency and reliability of the cloud data center. Secondly, in the load balancing method based on multi-objective multi-agent optimization we proposed, we designed a novel multi-objective collaborative optimization mechanism, which accelerates the convergence of the Pareto frontier through a dual-elite strategy. Thirdly, we also proposed an archive clipping mechanism based on crowded distance to maintain the diversity of the solution set. Finally, we conducted a large number of experiments in real cloud environments and large-scale simulations.
# Dataset Description
In this paper, we use the Alibaba 2021 microservices cluster data, which can be downloaded from [here](https://github.com/alibaba/clusterdata/tree/master/cluster-trace-microservices-v2021).
The first column is the node ID.
The second column is the CPU requested by each task.
The third column is the memory requested by each task.
