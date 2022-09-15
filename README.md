# Envoy-Proxy
Configuring Envoy proxy to route mirrored traffic to 2 backends Mirror Policies to be used

Create two EKS Clusters(Blue-Green)

1. Deploy your applications in the EKS clusters.
2. Follow Blue Green Deployment Strategy.
3. One of your EKS cluster should depict Blue while the other Green.
4. Expose your Services on the NodePort.
4. Spin up a fleet of EC2 instance or a single EC2 Instance.
5. Deploy/Download Envoy on it.
6. Create the Envoy Configuration file(yaml format).
7. To run envoy configuration file use:-

                  envoy -c /path/to/your-configuration.yaml file


For More Information Look into
   
   https://www.envoyproxy.io/docs/envoy/latest/api-v3/api
