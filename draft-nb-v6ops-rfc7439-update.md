---
title: "Updated Gap Analysis for Operating IPv6-Only MPLS Networks"
abbrev: "Operating IPv6-Only MPLS Networks"
category: info

docname: draft-nb-v6ops-rfc7439-update-latest
submissiontype: IETF
number:
date:
consensus: true
v: 3
area: "ops"
workgroup: "IPv6 Operations"
keyword:
 - IPv6
 - MPLS
venue:
  group: "IPv6 Operations"
  type: "Working Group"
  mail: "v6ops@ietf.org"
  arch: "https://mailarchive.ietf.org/arch/browse/v6ops/"
  github: "ietf-wg-v6ops/draft-nb-v6ops-rfc7439-update"
  latest: "https://ietf-wg-v6ops.github.io/draft-nb-v6ops-rfc7439-update/draft-nb-v6ops-rfc7439-update.html"

author:
 -
    fullname: Nick Buraglio
    organization: Energy Sciences Network
    email: "buraglio@forwardingplane.net"

normative:
  RFC7439:

informative:

--- abstract

This document reviews and updates the Multiprotocol Label Switching (MPLS)
protocol suite in the context of IPv6 and identifies remaining gaps that must
be addressed in order to allow MPLS-related protocols and applications to be
used with IPv6-only networks. This document is intended to focus on what gaps
still exist in the standards defining the MPLS suite, and is not intended to
highlight particular vendor implementations (or lack thereof) in the context
of IPv6-only MPLS functionality, providing operators with
an update to [RFC7439].

In addition to the legacy MPLS protocol suite, the tooling, capabilities, MPLS has expanded in breadth
and simplified in complexity with the advent of segment routing and SRv6. This document updates RFC 7439
to include those contemporary feature sets compliance with running in an IPv6-only environment.

--- middle

# Introduction

TODO Introduction

# Conventions and Definitions

{::boilerplate bcp14-tagged}
# Use Case

# Gap Analysis

# MPLS Data plane

# MPLS Control plane

## MPLS-SR

### SR-TE

### Segment Routing (SR) Point-to-Multipoint (P2MP)

## Topology-Independent Loop-Free Alternate (TI-LFA) Fast Reroute (FRR)

## SRv6

## RSVP - Traffic Engineering (RSVP-TE)

### Interior Gateway Protocol (IGP)

# Security Considerations

TODO Security

# IANA Considerations

This document has no IANA actions.

--- back

# Acknowledgments
The authors would like to thank Wes George, for their input and comments.
{:numbered="false"}

TODO acknowledge.
