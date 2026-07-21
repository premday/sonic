---
title: Tested Platforms
weight: 1
---

A list of switches qualified and validated by the Premday usergroup. Every entry on this page reflects real-world experience from members
who have deployed and operated SONiC on the listed hardware.

{{< callout >}}
To appear on this list:
* The hardware must have been qualified or used in production by at least one usergroup member.
* The vendor must have agreed to be listed.
{{< /callout >}}

The Premday stamp reflects the level of real-world experience usergroup members have with the platform:

* <span style="color:green">✓</span> **In production** — the platform is actively running production traffic by at least one usergroup member.
* <span style="color:blue">{{< icon "beaker" >}}</span> **Qualified** — the platform has been validated in a lab or evaluation setup, but is not (yet) running in a usergroup member's production.

Only validated features are listed. A missing feature does not necessarily mean it does not work: it may not have been validated successfully, it may have known limitations, or it may simply not be used by the usergroup member running the platform.

| Vendor | Model          | Ports    | Community SONiC branches | Platform drivers | SAI              | Validated features                                                                                                                          | Premday stamp                                                        |
|--------|-----------------|----------|--------------------------|------------------|------------------|---------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------|
| Micas  | M2-W6510-32C    | 32x100G  | 202305 | Open source | Community SAI | <span style="color:green">✓</span> BGP<br><span style="color:green">✓</span> VLAN<br><span style="color:green">✓</span> SNMP<br><span style="color:green">✓</span> ZTP<br><span style="color:green">✓</span> DHCP relay<br><span style="color:green">✓</span> IPv6<br><span style="color:green">✓</span> RFC 8950        | <span style="color:green">✓</span> In production                     |
| Micas  | M2-W6940-64OC   | 64x800G  | 202505 | Open source | Community SAI    | <span style="color:green">✓</span> BGP<br><span style="color:green">✓</span> SNMP<br><span style="color:green">✓</span> ZTP<br><span style="color:green">✓</span> DHCP relay<br><span style="color:green">✓</span> IPv6<br><span style="color:green">✓</span> RFC 8950                                                                                                      | <span style="color:blue">{{< icon "beaker" >}}</span> Qualified         |
| Nokia  | 7220 IXR-H5-64O | 64x800G  | 202505 | Open source | Community SAI    | <span style="color:green">✓</span> BGP<br><span style="color:green">✓</span> SNMP<br><span style="color:green">✓</span> ZTP<br><span style="color:green">✓</span> DHCP relay<br><span style="color:green">✓</span> IPv6<br><span style="color:green">✓</span> RFC 8950                                                                                                      | <span style="color:blue">{{< icon "beaker" >}}</span> Qualified         |
