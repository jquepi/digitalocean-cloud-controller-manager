# Load Balancers

## UDP Support

If your load balancer has UDP service ports you must configure a TCP service as a health check for the load balancer to work properly.

Note: currently, a port cannot be shared between TCP and UDP due to a [bug in Kubernetes](https://github.com/kubernetes/kubernetes/issues/39188).
