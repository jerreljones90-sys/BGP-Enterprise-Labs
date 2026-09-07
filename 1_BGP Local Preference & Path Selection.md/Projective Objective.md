# Project Objective # 

The objective of this lab is to configure Local Preference so that R2 receives a Local Preference value of **500 from R1**, causing R2 to prefer R1 as the exit path for the selected BGP prefixes.

Use the BGP Local Preference attribute to demonstrate how outbound traffic is influenced when leaving an Autonomous System (AS).

Local Preference is an internal BGP (iBGP) attribute used to determine the preferred exit path from an AS. A higher Local Preference value is preferred over a lower value.


VALIDATION: Traceroute and BGP verification commands will be used before and after applying the Local Preference policy to demonstrate how the preferred traffic path changes.

(( To view the topology and configs  please see the folder called Bgp Network Topology LP))
