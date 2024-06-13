# Description

The vpc.yaml is for CSI AWS CAD/RMS deployment use.

![image](https://github.com/carldi/cloudformation-csi/assets/45005576/51ba4376-863f-40ee-a3a2-31846d81fde7)

Next:
  1. Add TGW subnets
  2. Add attachment
  3. Add subnet route directory service -> TGW (AD)(new VPC)
  4. Add directory service route (AD)(Directory VPN)
  5. Add new VPC to on-prem firewall tunnel route (RDP)(on-prem)
  6. Add route to RDGW (RDP)(new VPC)
  7. Add Gateway Endpoint
  8. Update the route table to direct s3 traffic to the gateway endpoint
