---
title: "Making RFC and Internet-Draft Boilerplate Less Conspicuous"
category: info

docname: draft-thomson-rswg-bottom-fluff-latest
submissiontype: editorial  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
v: 3
area: "RFC Editor"
workgroup: "RFC Series Working Group"
keyword:
 - next generation
 - unicorn
 - sparkling distributed ledger
venue:
  group: "RFC Series Working Group"
  type: "Editorial Stream Working Group"
  mail: "rswg@rfc-editor.org"
  arch: "https://mailarchive.ietf.org/arch/browse/rswg/"
  github: "martinthomson/bottom-fluff"
  latest: "https://martinthomson.github.io/bottom-fluff/draft-thomson-rswg-bottom-fluff.html"
pi:
 toc: false

author:
 -
    fullname: "Martin Thomson"
    organization: Mozilla
    email: "mt@lowentropy.net"
 -
    fullname: "David Schinazi"
    organization: Google
    email: "dschinazi.ietf@gmail.com"

normative:

informative:

...

--- abstract

This document establishes a new policy for RFCs and Internet-Drafts
that moves all the fluff
(copyright notices and that sort of thing)
to the bottom of documents.

--- middle

# New Policy

No one reads the legal shrink wrap.
All we do by forcing it under their noses is annoy them
and waste their time.

The IETF can better serve its audience
by moving boilerplate in RFCs and Internet-Drafts
to the bottom of documents.
This ensures that notices exist,
but are minimally annoying.

# Precedent

In the beginning, there was no fluff (e.g., {{?RFC0768}}).
When fluff first started, the "status of this memo" section mainly served as an abstract (e.g., {{?RFC0959}}).
Later, its substantive contents were moved down to an "abstract" section (e.g., {{?RFC1601}}).
Eventually, someone noticed that having the fluff before the abstract was unhelpful, so the abstract was placed first (e.g., {{?RFC5545}}).
We are now following a long tradition of moving the fluff further and further down in the document.

# Security Considerations

The obvious argument is that placement of notices is a security feature.
However, given the wide acceptance of the fact that security by obscurity is not an adequate defense,
the use of obscurity to improve usability equally cannot be expected to degrade security.


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

The Internet Protocol Mercenary Company (IPMC) are acknowledged
for continuing their ongoing defense of the intellectual property in RFCs.

