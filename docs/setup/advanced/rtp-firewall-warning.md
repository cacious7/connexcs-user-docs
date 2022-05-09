# RTP Firewall Warning

A firewall controls the incoming and outgoing network traffic based on an applied rule set and establishes a barrier between a trusted, secure LAN and/or WAN network(s) and the internet. ConnexCS recommends a LAN architecture where the voice traffic bypasses the firewall.

Locked: RTP Firewall Warning lets the customers strictly use the existing RTP Firewall under Locked. This should be used only when your customers have specifically firewalled ConnexCS Media Ips.

Unlocked: RTP Firewall Warning lets the customers use the existing RTP Firewall in full flexibility. This allows ConnexCS to move your media to new different IP addresses automatically to achieve the best performance, reliability and scalability.

# Firewall

The ConnexCS **Firewall** uses a threat detection system to blacklist attackers.

## Threat Detection System
**Threat Detection** is always on and, along with other key identifiers, analysing traffic hitting our platform. It primarily pays attention to authentication failures on both registration and firewall of a particular threshold. If certain criteria are exceeded the system will issue a system wide block.

## Remove an IP from the Blocked list
Should a valid attempt from your customer or carrier be blocked inadvertently, you can correct this by clicking on the checkbox by the IP address and clicking on the delete icon.

!!! note "Updating removed IP"
    It can take up to 15 minutes after an IP has been removed from the block list before it is updated across the entire platform.

## False Positive
If you have a customer or carrier who sends a large volume of *unauthorized* calls, it is possible that they will be added to the Block list.

## False Negatives
You may see attempts hitting your switch which are not authorized and then fail. These are attempts which our system has successfully declined the call to process. There is no need to take further action to stop these calls.

It is important that calls such as these are visible for 2 reasons.

1. If we block an IP address too quickly, this may be a customer who is trying to interconnect with you. Once blocked, you lose the ability to view debugging information since the packets are dropped prior to logging.
2. If we block too soon, we lose the ability to ascertain any attack patterns and profiling information on an attack. Having some data allows us to see progressive attacks spanning multiple IP addresses.