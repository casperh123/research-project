# Prelimenary problem statement and project proposal

## Motivation

LoRaWAN for *(maritime)* positioning to be used in areas where GPS signal quality is unsuitable for use. 

## Project proposal


### Prelimenary problem statement ideas

Context? -> What are we interested in? -> State of the art? -> Problem? -> Outline specific solution idea -> Method and deliverable

Maritime navigation in the Baltic Sea is under sustained threat from GPS jamming and spoofing, attributed to Russian electronic warfare activity since 2022. The scale of the problem is now significant enough that thirteen European nations and Iceland issued a joint warning in January 2026, and recent research confirms that spoofing is a daily operational reality for vessels in the region, not a theoretical risk. Without reliable positioning, vessels navigating the Baltic Sea face real risk of course deviation, straying into restricted or hazardous waters, and general navigational error, with direct consequences for maritime safety. GNSS-independent alternatives are therefore needed to supplement navigation in these affected areas. LoRaWAN is a promising candidate: existing research demonstrates that LoRaWAN-based geolocation, using methods such as TDoA and RSSI-based techniques, is feasible on land and in maritime contexts, with long-range coverage achievable even over open water. However, its application specifically as a GNSS-independent positioning supplement for vessels in GPS-degraded maritime areas remains underexplored, and multi-hop or mesh extensions for this use case are an immature area of research. This project will implement a LoRaWAN-based geolocation system as a GNSS-independent supplement for use in these GPS-degraded areas, and establish how accurate such a system can realistically be made. The approach will proceed through a literature review, simulation of network coverage and positioning accuracy, and a small-scale prototype, either land-based or in Øresund, to validate the theoretical findings.

Motivation:
It can maybe be used in areas where GPS is unreliable.

Q1: How precise is LoRaWAN geolocation when used as a maritime navigational aid?

LoRaWAN for positioning.
To be used in areas where GPS signal quality is unsuitable for use.
Cheap.
Low power.
Long distance.
Can maybe be used when GPS is unreliable.
