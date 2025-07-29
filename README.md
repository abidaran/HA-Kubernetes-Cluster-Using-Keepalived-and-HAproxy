A highly available Kubernetes cluster ensures your applications run without outages which is required for production. 
Keepalived provides a VRPP implementation and allows you to configure Linux machines for load balancing, preventing single points of failure. HAProxy, providing reliable, high performance load balancing, works perfectly with Keepalived.
HAproxy Configuration
The configuration of HAproxy is exactly the same on the two machines for load balancing. Run the following command to configure HAproxy.
Keepalived Configuration
Keepalived must be installed on both machines while the configuration of them is slightly different.

