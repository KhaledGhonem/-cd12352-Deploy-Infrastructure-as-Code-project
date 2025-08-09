# CD12352 - Infrastructure as Code Project Solution
# Khaled Ibrahim

## Infrastructure Diagram
![Udagram Infrastructure](./Udagram-Infrastructure-Diagram.png)

## Spin up instructions
- ./create.sh udagram-netowrk-stack network.yml network-parameters.json
- ./create.sh udagram-s3bucket-stack s3bucket.yml s3bucket-parameters.json
- ./create.sh udagram-stack udagram.yml udagram-parameters.json

## Tear down instructions
- ./delete.sh udagram-stack
- ./delete.sh udagram-s3bucket-stack
- ./delete.sh udagram-network-stack

## Other considerations
The DNS name of the load balancer is [Udagram App](http://udagra-webap-i0pfs0btdbxk-377872818.us-east-1.elb.amazonaws.com/)