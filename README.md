# LAMPS EST renewal recommendations

This document describes an extension to RFC7030, Enrollment over Secure Transport to
give an indication to a end-entity device when it should start attempting to renew its certificates.

Prior art is that client decides, with a typical recommmendation to start when the remaining lifetime of the certificate is at the 50% point.
As typical certificate lifetimes are reduced from years to fractions of a year, the 50% may be far too early, and this document provides a way to give alternate advice.

https://github.com/mcr/lamps-rfc7030-renewal-recommendation.git
