
- **types of UAV network**
	1. `single-UAV network`: the UAV is linked to a ground base station or to satellite 
	2. `Mulit-UAV network`: multiple UAV devices are linked  to each other in addition to the ground base station or satellite
- `his is the first article thatstudies all categories of routing protocols reported in the iterature`
- this paper compare all categories  of routing  procole like 
	- position-based 
	- topology-based 
	- cluster-based 
	- deterministic 
	- stochastic 
	- social network based 
#### DESIGN CONSIDERATIONS FOR UAV NETWORKS
##### A. TOPOLOGY
- P2P connections formed for UAV to maintain coordination and collaboration
	1. single-cluster is the best for homogenous and small scale missions
	2. multi-cluster  is for multiple missions  
		1. the cluster head of each cluster is responsible to  link communication between other \ head ![1](https://github.com/user-attachments/assets/7cb168ef-0c6e-4266-bc09-bc7ccad6ead5)

##### B.COMMUNICATION IN UAV NETWORK 
- please read this [MANET vs VANET vs FANET](https://www.rfwireless-world.com/Terminology/MANET-vs-VANET-vs-FANET.html)![FANET-vs-VANET-vs-MANET](https://github.com/user-attachments/assets/84354402-07a4-4d08-93d2-91344ecf7733)

	- FANETs use MAC protocole like IEEE 802.11 for high-bandwidth and long-range UAV-to-ground link while IEEE 802.14.4 for low-power ,low bandwidth UAV-to-UAV 
	- ==the chalnges is 1.managing delays , optimaizing channels , and handling fluctuating link quality while high mobility== 
	1. AIR-TO-AIR WIRELESS COMMUNICATION
		- to avoid restricions on the transimission range UAV just communicate in ad hoc network Archi 
	2. AIR-TO-GROUND WIRELESS COMMUNICATION 
		- few UAV can communicat with the ground only a select few do to imporve connectivity , plus delivery of other services
---
### DESIGN TECHNIQUES FOR ROUTING IN UAV NETWORKS
 **A. DELIVERY SCHEME**
 
![2](https://github.com/user-attachments/assets/cc5919b0-feee-4eb9-9a3e-68a2754b5f47)

**B.COOPERATIVE ROUTING**
- used to increase the reliability of communication 
	- *CT*: cooperative transmission
	- *DT*: direct transmission
 
![3](https://github.com/user-attachments/assets/11a06910-0802-46b5-a77c-f2d3e8397d35)
