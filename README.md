## Minecraft Scanners List

A ip list to specifically block minecraft scanners.

### Why block these?
* Performance, mass pings can cause a DoS effect.  Additionally modded servers may suffer misc performance issues from frequent pings.
* Annoyance, these pings clutter up the server logs, analytics, and are just rather annoying.
* Security, while security through obscurity is no security.  It does help reduce the amount of garbage pointed in your direction.

### Criterias to be IP listed?
* No AWS/Oracle or other dynamic cloud providers, with the only exception to being mass IP scanning from a single address over a long period of time.
* No dynamic/residential IPs - No point in adding these as they will change to frequently.
* No tor/proxies - Can easily be covered by a generic tor/proxy blacklist

### Criterias to be Subnet listed?
* All the previous criterias are met
* The subnet or ASN has a poor reputation per (here)[https://talosintelligence.com/reputation_center/]



### ASN Offenders:
* PFCloud - They are by far the worst offenders of allowing this activity