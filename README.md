# o365_split_tunnel_acl

<GRP_POLICY_NAME>: Split-SINOG<br/>
<ACL_NAME>: MS-O365<br/>
<br/>
group-policy <GRP_POLICY_NAME> attributes<br/>
vpn-tunnel-protocol ssl-client ssl-clientless<br/>
&nbsp;&nbsp;split-tunnel-policy excludespecified<br/>
&nbsp;&nbsp;split-tunnel-network-list value <ACL_NAME><br/>
