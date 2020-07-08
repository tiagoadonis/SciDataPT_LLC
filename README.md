# SciDataPT, LLC

SciDataPT, LLC is a data analisys services provider company with a strong cientific investigation component. The company has HQ in three different 
locations, Aveiro, Lisboa and Boston. In every HQ exists only services provision departments besides Aveiro where stands a cientific investigation 
department.

The company reshaped their instalations and add two more building with 5 floors in Aveiro, one in Lisboa and other one in Boston, all with the 
same caracteristics.

There are global datacenters in Aveiro and Boston to provide processing and storage to every building in this locations. In Aveiro still exists one 
local datacenter in the cientific investigation building.  

The company made a deal with two portuguese ISP (ISP PT1 and ISP PT2) to provide internet to Aveiro and Lisboa HQ but the ISP PT2 doesn't suport IPV6 
routing. When it comes to Boston, the two ISP that provide internet are ISP US1 and ISP US2.

It must be guaranted the confidentiality **(i)** internal between Aveiro's investigation VLAN and the local datacenter, **(ii)** external between Aveiro's
administration VLAN and Boston's administration. 

All the network traffic between Aveiro and Lisboa should be redirected to a specific micro-wave antenna.

All the distribuiton by floor and building are in the [Network Analysis](https://github.com/tiagoadonis/SciDataPT_LLC/blob/master/Documentation/Network%20Analysis.pdf).
The diagram of the network is [here](https://github.com/tiagoadonis/SciDataPT_LLC/blob/master/Documentation/Network%20Diagram.pdf), and all the details of
the equipments used is [here](https://github.com/tiagoadonis/SciDataPT_LLC/blob/master/Documentation/Equipment%20Requirements.pdf).

### Images used in GN3 implementation:

- Cisco router 7200 15.1(4) - Minimum RAM: 512MB - 1x C7200-IO-2FE and 3x PA-2FE-TX  
- Cisco router 3725 12.4(21) - Minimum RAM: 256 MB - 1x GT96100-FE and 1x NM-1FE-TX
- LXDE 8.10 in Debian (for the global datacenter)
