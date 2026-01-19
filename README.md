# Secure Network Segmentation in Azure

## Objective
The goal of this lab was to design and secure an Azure virtual network
using segmented subnets and firewall rules to restrict access and reduce
the attack surface.

## Architecture Overview
- Azure Virtual Network (10.0.0.0/16)
- Public subnet (10.0.1.0/24)
- Private subnet (10.0.2.0/24)
- Subnet-level Network Security Groups (NSGs)

## Security Controls Implemented
- Applied NSG to public subnet, allowing SSH only from a trusted IP
- Enforced default deny inbound rules on private subnet
- Used network segmentation to isolate internal resources

## Validation
- Verified inbound rules on public NSG
- Confirmed no inbound access to private subnet
- Reviewed default deny behavior

## Key Takeaways
- Learned how Azure VNets and subnets are structured
- Gained experience with NSGs and firewall rules
- Understood how segmentation improves cloud security
