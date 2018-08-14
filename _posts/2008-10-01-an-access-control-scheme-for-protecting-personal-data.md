---
author: "W. Villegas, B. Ali, and M. Maheswaran"
title: "An Access Control Scheme for Protecting Personal Data"
journal: "Sixth Annual Conference on Privacy, Security and Trust (PST 2008)"
location: "pp. 24-35, New Brunswick, Canada"
date: 2008-10-01
---
We present a personal data access control (PDAC) scheme inspired by protection schemes used in communities for sharing valuable commodities. We assume PDAC users are members of an online social network such as facebook.com. PDAC computes a “trusted distance” measure between users that is composed of the hop distance on the social network and an affine distance derived from experiential data. The trusted distance classifies users into three zones: acceptance, attestation, and rejection. User requests falling in the acceptance zone are accepted immediately while the requests in the rejection zone are rejected outright. Requests in the attestation zone need additional authorization to gain access. PDAC also tracks reposts to minimize the spread of data beyond the limits set by the data originator. PDAC was implemented on a social network emulator to demonstrate its viability. The performance of certain PDAC functions were examined using simulations driven by portions of social graphs obtained from myspace.com.