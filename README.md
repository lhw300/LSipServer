 
# LSipServer

LSipServer is a Java-based SIP server built on Apache Tomcat, designed for
call center and softswitch scenarios.

It focuses on SIP signaling, session control, and practical deployment
requirements in real-world VoIP and contact center environments.

## Overview
LSipServer is implemented in Java and built on a standards-compliant
JAIN-SIP stack. The SIP stack is based on the NIST (usnistgov) JAIN-SIP
reference implementation, with selected bug fixes  and stability improvements
applied for production use. The modified JAIN-SIP binaries are included
in the released distribution.

The system architecture separates SIP signaling, RTP/media handling,
and web-based management components, making it suitable for both
standalone SIP server deployments and integration into larger
call center platforms.

## My Role

I am the sole developer responsible for the architecture, SIP/RTP implementation, 
and bug fixing, optimization of this product.

## Technical Focus
- SIP signaling, registration, and session management
- Java-based SIP server and softswitch architecture
- Apache Tomcat–based web container
- Modified NIST JAIN-SIP reference implementation with bug fixes(by Harvey Liu),
  original project: https://github.com/usnistgov/jsip
- RTP relay support for SIP proxy and NAT/private network scenarios
- Practical, production-oriented design based on real-world deployments

## RTP Relay Support
LSipServer includes an RTP relay component designed for deployments where
the SIP proxy operates in private or NATed network environments. This allows
media streams to be properly relayed between endpoints when direct RTP
connectivity is not available.

 
## Availability (Free Edition)
LSipServer is available as a free edition provided by LCALL (xiaolinghu) for
evaluation and internal use.

## Download:
http://www.it9000.cn/file/lsip.zip   (windows)

## License
LSipServer is free to download and use, including for commercial purposes.
Redistribution of the original binary package is permitted.

The software is provided as-is and may not be reverse engineered or modified.
Third-party components are subject to their own licenses, which are included in the distribution archive.
See LICENSE and NOTICE for details.

This product is distributed as a binary-only package.


## Author
**Harvey Liu**  
Sole Developer
Email: **lhw300@163.com**

Harvey has many years of hands-on experience in SIP, softswitch, RTP/media
handling, and call center system development, including independent
development of Java-based SIP servers and VoIP platforms.
