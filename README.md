 
# LSipServer

LSipServer is a Java-based SIP server built on Apache Tomcat, designed for
call center and softswitch scenarios.

It focuses on SIP signaling, session control, and practical deployment
requirements in real-world VoIP and contact center environments.

## Overview
LSipServer is implemented in Java and built on a standards-compliant
JAIN-SIP stack. The SIP stack is based on the NIST (usnistgov) JAIN-SIP
reference implementation, with selected bug fixes and stability improvements
applied for production use. The modified JAIN-SIP binaries are included
in the released distribution.

The system architecture separates SIP signaling, RTP/media handling,
and web-based management components, making it suitable for both
standalone SIP server deployments and integration into larger
call center platforms.

## Technical Focus
- SIP signaling, registration, and session management
- Java-based SIP server and softswitch architecture
- Apache Tomcat–based web container
- Modified NIST JAIN-SIP reference implementation with bug fixes
- RTP relay support for SIP proxy and NAT/private network scenarios
- Practical, production-oriented design based on real-world deployments

## RTP Relay Support
LSipServer includes an RTP relay component designed for deployments where
the SIP proxy operates in private or NATed network environments. This allows
media streams to be properly relayed between endpoints when direct RTP
connectivity is not available.

## Download
Please download the binary distribution from the Releases page.

## License
This product is distributed as a binary-only package.
Third-party license information is included in the distribution archive.

## Author
LSipServer is developed and maintained by:

**Harvey Liu**  
Email: **lhw300@163.com**

Harvey has many years of hands-on experience in SIP, softswitch, RTP/media
handling, and call center system development, including independent
development of Java-based SIP servers and VoIP platforms.
