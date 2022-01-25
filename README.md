# GNS3-BGP-MPLS-VPN
Simple implementation of an MPLS provider core network and two client networks interconnected via BGP using VRFs.

Using a core network composed of 4 core routers (MPLS/OSPF) and two edge routers (BGP/OSPF/MPLS), the objective is to connect two client entities.

Distributed on 4 AS and two common entities, we make transit packets via a tunnel between two AS having behind the same ip subnets.

Using VRFs associated with physical interfaces, the edge routers are able to forward the packets to the subnets corresponding to each entity. 

