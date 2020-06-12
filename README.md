# Big-data-stream-processing-in-the-Fog-and-Cloud-environnement
In this project we have explored some data streaming  and data science techniques to prove the following assumption:  Streaming the applications in the Edge+Cloud is much better than streaming them only in the Cloud. The supervisor has given me the opportunity to reserve nodes in different locations to simulate first the Cloud environnement: Powerful nodes in terms of hardware and also to simulate the Edge+Cloud environnement where we mitigate some powerful nodes to be the cloud and other powerless nodes to be the Edge. We have used this reserved nodes to install Storm and then to stream one prototype generator application named : NAMB over the Storm installed. At the end of the streaming, we have retrieved the log files that contain a list of tuples generated in the reserved nodes to parse them and then calculate the throughput and the latency of the streaming of the Application NAMB over Storm first in the Cloud only and then in the Edge+Cloud to compare them and check if our assumption is valid or not.
