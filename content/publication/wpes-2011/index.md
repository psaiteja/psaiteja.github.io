---
title: 'Cover locations: availing location-based services without revealing the location'
authors:
- Sai Teja Peddinti
- Avis Dsouza
- Nitesh Saxena
date: '2011-01-01'
publishDate: '2025-07-30T18:33:35.047732Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 10th Annual ACM Workshop on Privacy in the Electronic
  Society*'
doi: 10.1145/2046556.2046576
abstract: Location-Based Services (LBSs) have been gaining popularity due to a wide
  range of interesting and important applications being developed. However, the users
  availing such services are concerned about their location privacy, in that they
  are forced to reveal their sensitive location information to untrusted third-parties.
  In this paper, we propose a new privacy-preserving approach, Cover Locations, which
  allows a user to access an LBS without revealing his/her actual location. Based
  on its current location, the user's device queries for a few specifically chosen
  surrounding locations and constructs the results corresponding to its location from
  the results obtained for each queried location. Since the user location does not
  leave the user's device - as either a latitude and longitude pair, or as an obfuscated
  region - the user is guaranteed very high level of privacy. The Cover Locations
  approach only requires minimal changes on the user's device and can be readily deployed
  by privacy-conscious users. An adversary, trying to identify the user location,
  can only resolve the location to few triangular regions and not to the actual location
  itself. We evaluate the privacy provided by Cover Locations based on the number
  of locations queried and the total area under the resolved triangular regions. We
  also ascertain the robustness of Cover Locations approach when the adversary has
  access to a short-term user history, employing machine learning techniques. Overall,
  our results show that the proposed solution, which requires minor computations without
  the need for any out-of-band information such as traffic densities in a region or
  the road network information, is superior to other client-based solutions.
tags:
- k-anonymity
- location privacy
- location-based services
links:
- name: URL
  url: https://doi.org/10.1145/2046556.2046576
---
