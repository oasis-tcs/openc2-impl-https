![OASIS Logo](image_0.png)

---

# Specification for Transfer of OpenC2 Messages via HTTPS Version 1.0
## Working Draft 01
## 15 June 2018
#### Specification URIs
##### This Version:
[http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd01.md](http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd01.md) (Authoritative)

[http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd01.html](http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd01.html)

[http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd01.pdf](http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd01.pdf)

##### Previous Version:
N/A

##### Latest Version:
[http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.md](http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.md) (Authoritative)

[http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.html](http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.html)

[http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.pdf](http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.pdf)

##### Technical Committee:
[OASIS Open Command and Control (OpenC2) TC](https://www.oasis-open.org/committees/openc2/)

##### Chairs:
* Joe Brule ([jmbrule@nsa.gov](mailto:jmbrule@nsa.gov)), [National Security Agency](https://www.nsa.gov/)
* Sounil Yu ([sounil.yu@bankofamerica.com](mailto:sounil.yu@bankofamerica.com)), [Bank of America](http://www.bankofamerica.com/)

##### Editor:
* David Lemire ([dave.lemire@g2-inc.com](mailto:dave.lemire@g2-inc.com)), [G2, Inc.](http://www.g2-inc.com/))

##### Additional artifacts:
This prose specification is one component of a Work Product that also includes:  

* XML schemas: [http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/schemas/](http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/schemas/)
* Other parts

> **Note to Editor**: List the full title and VISIBLE hyperlink, including the terminating slash ("/"). The hyperlink should link to an HTML version, if possible.
> 
> Remove entire section if there are no entries. Don't use "N/A".

##### Related work:
This specification replaces or supersedes:  

* Specifications replaced by this specification 

This specification is related to:  

* Related specifications

> **Note to Editor**: List the VISIBLE hyperlink to an HTML version, if possible.
> 
> Remove entire "Related work" section or the "replaces" or "related" subsections if there are no entries.

##### Declared XML namespaces:
* list namespaces which are declared, not just referenced

> **Note to Editor**: List the VISIBLE hyperlink, if HTTP-based URI.
> 
> Remove entire section if there are no entries. Don't use "N/A".

## Abstract:
This specification describes the use of HTTP over TLS as a transfer mechanism for OpenC2 messages. It explains the transfer of OpenC2 command and response messages using HTTP and the use of TLS to provide security.

## Status:
This document was last revised or approved by the OASIS Open Command and Control (OpenC2) TC on the above date. The level of approval is also listed above. Check the "Latest version" location noted above for possible later revisions of this document. Any other numbered Versions and other technical work produced by the Technical Committee (TC) are listed at [https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=openc2#technical](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=openc2#technical).

TC members should send comments on this specification to the TC's email list. Others should send comments to the TC's public comment list, after subscribing to it by following the instructions at the "[Send A Comment](https://www.oasis-open.org/committees/comments/index.php?wg_abbrev=openc2)" button on the TC's web page at [https://www.oasis-open.org/committees/openc2/](https://www.oasis-open.org/committees/openc2/).

This specification is provided under the [Non-Assertion](https://www.oasis-open.org/policies-guidelines/ipr#Non-Assertion-Mode) Mode of the [OASIS IPR Policy](https://www.oasis-open.org/policies-guidelines/ipr), the mode chosen when the Technical Committee was established. For information on whether any patents have been disclosed that may be essential to implementing this specification, and any offers of patent licensing terms, please refer to the Intellectual Property Rights section of the TC's web page ([https://www.oasis-open.org/committees/openc2/ipr.php](https://www.oasis-open.org/committees/openc2/ipr.php)).

Note that any machine-readable content ([Computer Language Definitions](https://www.oasis-open.org/policies-guidelines/tc-process#wpComponentsCompLang)) declared Normative for this Work Product is provided in separate plain text files. In the event of a discrepancy between any such plain text file and display content in the Work Product's prose narrative document(s), the content in the separate plain text file prevails.

### Citation format:
When referencing this specification the following citation format should be used:

**[OpenC2-HTTPS-v1.0]**

_Specification for Transfer of OpenC2 Messages via HTTPS Version 1.0_. Edited by David Lemire. 11 June 2018. OASIS Committee Specification Draft 01. [http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd01.html](http://docs.oasis-open.org/openc2/open-impl-https/v1.0/csd01/open-impl-https-v1.0-csd01.html). Latest version: [http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.html](http://docs.oasis-open.org/openc2/open-impl-https/v1.0/open-impl-https-v1.0.html).

---

## Notices
Copyright © OASIS Open 2018. All Rights Reserved.

All capitalized terms in the following text have the meanings assigned to them in the OASIS Intellectual Property Rights Policy (the "OASIS IPR Policy"). The full [Policy](https://www.oasis-open.org/policies-guidelines/ipr) may be found at the OASIS website.

This document and translations of it may be copied and furnished to others, and derivative works that comment on or otherwise explain it or assist in its implementation may be prepared, copied, published, and distributed, in whole or in part, without restriction of any kind, provided that the above copyright notice and this section are included on all such copies and derivative works. However, this document itself may not be modified in any way, including by removing the copyright notice or references to OASIS, except as needed for the purpose of developing any document or deliverable produced by an OASIS Technical Committee (in which case the rules applicable to copyrights, as set forth in the OASIS IPR Policy, must be followed) or as required to translate it into languages other than English.

The limited permissions granted above are perpetual and will not be revoked by OASIS or its successors or assigns.

This document and the information contained herein is provided on an "AS IS" basis and OASIS DISCLAIMS ALL WARRANTIES, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTY THAT THE USE OF THE INFORMATION HEREIN WILL NOT INFRINGE ANY OWNERSHIP RIGHTS OR ANY IMPLIED WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.

OASIS requests that any OASIS Party or any other party that believes it has patent claims that would necessarily be infringed by implementations of this OASIS Committee Specification or OASIS Standard, to notify OASIS TC Administrator and provide an indication of its willingness to grant patent licenses to such patent claims in a manner consistent with the IPR Mode of the OASIS Technical Committee that produced this specification.

OASIS invites any party to contact the OASIS TC Administrator if it is aware of a claim of ownership of any patent claims that would necessarily be infringed by implementations of this specification by a patent holder that is not willing to provide a license to such patent claims in a manner consistent with the IPR Mode of the OASIS Technical Committee that produced this specification. OASIS may include such claims on its website, but disclaims any obligation to do so.

OASIS takes no position regarding the validity or scope of any intellectual property or other rights that might be claimed to pertain to the implementation or use of the technology described in this document or the extent to which any license under such rights might or might not be available; neither does it represent that it has made any effort to identify any such rights. Information on OASIS' procedures with respect to rights in any document or deliverable produced by an OASIS Technical Committee can be found on the OASIS website. Copies of claims of rights made available for publication and any assurances of licenses to be made available, or the result of an attempt made to obtain a general license or permission for the use of such proprietary rights by implementers or users of this OASIS Committee Specification or OASIS Standard, can be obtained from the OASIS TC Administrator. OASIS makes no representation that any information or list of intellectual property rights will at any time be complete, or that any claims in such list are, in fact, Essential Claims.

The name "OASIS" is a trademark of [OASIS](https://www.oasis-open.org/), the owner and developer of this specification, and should be used only to refer to the organization and its official outputs. OASIS welcomes reference to, and implementation and use of, specifications, while reserving the right to enforce its marks against misleading uses. Please see [https://www.oasis-open.org/policies-guidelines/trademark](https://www.oasis-open.org/policies-guidelines/trademark) for above guidance.

---

## Table of Contents
[[TOC]]

---

# 1 INTRODUCTION
The OpenC2 Language Specification [OpenC2-Lang-v1.0] defines a language used to compose messages for command and control of cyber defense systems and components.  A message consists of a set of headers and a body.

The OpenC2 language defines two message body types:

1. **Command**: An instruction from one system known as the OpenC2 "Producer", to one or more systems, the OpenC2 "Consumer(s)", to act on the content of the command
2. **Response**: Any information captured or necessary to send back to the OpenC2 Producer  system that requested the Command be invoked, i.e., the OpenC2 Consumer response to the OpenC2 Producer.

This specification defines the procedures and conventions used when using Hypertext Transfer Protocol (HTTP) and Transport Layer Security (TLS) for the transport of OpenC2 command and response messages between OpenC2 producers and consumers.

## 1.1 IPR Policy
This specification is provided under the [Non-Assertion](https://www.oasis-open.org/policies-guidelines/ipr#Non-Assertion-Mode) Mode of the [OASIS IPR Policy](https://www.oasis-open.org/policies-guidelines/ipr), the mode chosen when the Technical Committee was established. For information on whether any patents have been disclosed that may be essential to implementing this specification, and any offers of patent licensing terms, please refer to the Intellectual Property Rights section of the TC's web page ([https://www.oasis-open.org/committees/openc2/ipr.php](https://www.oasis-open.org/committees/openc2/ipr.php)).

## 1.2 Terminology
The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [[RFC2119](#RFC2119)] and [[RFC8174](#RFC8174)] when, and only when, they appear in all capitals, as shown here.

## 1.3 Normative References
**[RFC2119]**

Bradner, S., "Key words for use in RFCs to Indicate Requirement Levels", BCP 14, RFC 2119, DOI 10.17487/RFC2119, March 1997, <[http://www.rfc-editor.org/info/rfc2119](http://www.rfc-editor.org/info/rfc2119)>.

**[RFC2818]** 

Rescorla, E., "HTTP Over TLS", RFC 2818, DOI 10.17487/RFC2818, May 2000, <[https://www.rfc-editor.org/info/rfc2818](https://www.rfc-editor.org/info/rfc2818)>.

**[RFC5246]** 

Dierks, T. and E. Rescorla, "The Transport Layer Security (TLS) Protocol Version 1.2", RFC 5246, DOI 10.17487/RFC5246, August 2008, <[https://www.rfc-editor.org/info/rfc5246](https://www.rfc-editor.org/info/rfc5246)>.

**[RFC5280]** 

Cooper, D., Santesson, S., Farrell, S., Boeyen, S., Housley, R., and W. Polk, "Internet X.509 Public Key Infrastructure Certificate and Certificate Revocation List (CRL) Profile", RFC 5280, DOI 10.17487/RFC5280, May 2008, <https://www.rfc-editor.org/info/rfc5280>.

**[RFC7230] **

Fielding, R., Ed., and J. Reschke, Ed., "Hypertext Transfer Protocol (HTTP/1.1): Message Syntax and Routing", RFC 7230, DOI 10.17487/RFC7230, June 2014, <https://www.rfc-editor.org/info/rfc7230>.

**[RFC7231]** 

Fielding, R., Ed., and J. Reschke, Ed., "Hypertext Transfer Protocol (HTTP/1.1): Semantics and Content", RFC 7231, DOI 10.17487/RFC7231, June 2014, <https://www.rfc-editor.org/info/rfc7231>.

**[RFC7232]** 

Fielding, R., Ed., and J. Reschke, Ed., "Hypertext Transfer Protocol (HTTP/1.1): Conditional Requests", RFC 7232, DOI 10.17487/RFC7232, June 2014, <https://www.rfc-editor.org/info/rfc7232>.

**[RFC7233]** 

Fielding, R., Ed., Lafon, Y., Ed., and J. Reschke, Ed., "Hypertext Transfer Protocol (HTTP/1.1): Range Requests", RFC 7233, DOI 10.17487/RFC7233, June 2014, <https://www.rfc-editor.org/info/rfc7233>.

**[RFC7234]** 

Fielding, R., Ed., Nottingham, M., Ed., and J. Reschke, Ed., "Hypertext Transfer Protocol (HTTP/1.1): Caching", RFC 7234, DOI 10.17487/RFC7234, June 2014, <https://www.rfc-editor.org/info/rfc7234>.

**[RFC7235]** 

Fielding, R., Ed., and J. Reschke, Ed., "Hypertext Transfer Protocol (HTTP/1.1): Authentication", RFC 7235, DOI 10.17487/RFC7235, June 2014, <https://www.rfc-editor.org/info/rfc7235>.

**[RFC8174]**

Leiba, B., "Ambiguity of Uppercase vs Lowercase in RFC 2119 Key Words", BCP 14, RFC 8174, DOI 10.17487/RFC8174, May 2017, <http://www.rfc-editor.org/info/rfc8174>.

**[OpenC2-Lang-v1.0]**

_Open Command and Control (OpenC2) Language Specification Version 1.0_.

Edited by Jason Romano and Duncan Sparrell.

**[Reference]**

[Full reference citation]

* OpenC2 Language Specification

## 1.4 Non-Normative References
**[RFC3205]** 

Moore, K., "On the use of HTTP as a Substrate", BCP 56, RFC 3205, DOI 10.17487/RFC3205, February 2002, <https://www.rfc-editor.org/info/rfc3205>.

**[RFC6546]** 

Trammell, B., "Transport of Real-time Inter-network Defense (RID) Messages over HTTP/TLS", RFC 6546, DOI 10.17487/RFC6546, April 2012, <https://www.rfc-editor.org/info/rfc6546>.

**[RFC7525]** 

Sheffer, Y., Holz, R., and P. Saint-Andre, "Recommendations for Secure Use of Transport Layer Security (TLS) and Datagram Transport Layer Security (DTLS)", BCP 195, RFC 7525, DOI 10.17487/RFC7525, May 2015, <https://www.rfc-editor.org/info/rfc7525>.

**[OpenC2 Glossary]** 

OpenC2 Glossary. Edited by Duncan Sparrell and TODO. Date-TODO. OASIS TODO. link TODO.

**[Reference]**

[Full reference citation]

> **Note to Editor**:
> _Reference sources_:
> For references to **IETF RFCs**, use the approved citation formats at:
> [http://docs.oasis-open.org/templates/ietf-rfc-list/ietf-rfc-list.html](http://docs.oasis-open.org/templates/ietf-rfc-list/ietf-rfc-list.html).
> For references to **W3C Recommendations**, use the approved citation formats at:
> [http://docs.oasis-open.org/templates/w3c-recommendations-list/w3c-recommendations-list.html](http://docs.oasis-open.org/templates/w3c-recommendations-list/w3c-recommendations-list.html).
> 
> Remove this note before submitting for publication.

## 1.5 Overview
This specification describes the use of Hypertext Transfer Protocol (HTTP) over Transport Layer Security (TLS) as a transport mechanism for OpenC2 messages; this HTTP/TLS layering is typically referred to as HTTPS. As described in [RFC3205], HTTP has become a common "substrate" for information transfer for other application-level protocols. The broad availability of HTTP makes it a useful option for OpenC2 message transport in support of prototyping, interoperability testing, and for operational use in environments where appropriate security protections can be provided. Similarly, TLS is a mature and widely-used protocol for securing information transfers in TCP/IP network environments. This specification provide guidance to the OpenC2 implementation community when utilizing HTTPS for OpenC2 message transport.

# 2 OPERATING MODELS
This section describes the operating models associated with the available assignments of endpoint roles with regard to OpenC2 and HTTP.

## 2.1 	Endpoint Definitions
Each endpoint of an OpenC2-over-HTTPS interaction has both an OpenC2 role and an HTTP role. As defined in the [OpenC2 Glossary], one end will be an OpenC2 Producer and the other a Consumer. In the HTTP realm, one end will be an HTTP client and the other an HTTP server (i.e., listener). Depending on the nature of the communications environment, it can be feasible to map either of the OpenC2 Producer or the Consumer roles to either of the HTTP functions. In some environments, other networking considerations may limit the alignment of the roles. For example, if the OpenC2 Consumer is located behind a router that performs network port and/or address translation, it may not be practicable for the Producer to contact an HTTP server listening on behalf of the Consumer. In contrast, a collection of virtual machines in a cloud environment could easily allow any VM to be either a listening HTTP server or a requesting HTTP client or both, offering much greater flexibility.

	

[RFC6546], _Transport of Real-time Inter-network Defense (RID) Messages over HTTP/TLS_, addresses this situation by specifying an arrangement where each RID server is both an HTTP/TLS server and an HTTP/TLS client. Given the anticipated range of implementation environments for OpenC2, a more flexible approach appears justified, so this specification allows for three implementation configurations:

	

* The OpenC2 Producer is the HTTP server
* The OpenC2 Consumer is the HTTP server
* Both OpenC2 Producer and Consumer are HTTP servers

	

The OpenC2 role associated with the HTTP listener is identified by the port on which the server is listening.

	

**EDITOR'S NOTE:** Pending any official port assignments this document will use **pPROD** and **pCONS** to identify the ports where the listener is the OpenC2 Producer and Consumer, respectively.

The following sections briefly summarize each of these operating models. Details of how the models are implemented are provided in Section 3 and example interactions are described in Appendix B.

## 2.2 OpenC2 Consumer as the HTTP server
Figure 1 illustrates the configuration where the OpenC2 Consumer operates an HTTP server listening on port pCONS. In this configuration, a Producer that needs to send OpenC2 commands initiates a TCP connection to the Consumer on pCONS. Once the TCP connection is created, a TLS session is initiated to authenticate the endpoints and provide connection confidentiality. The Producer can then directly issue OpenC2 commands using the HTTP POST method, with Consumer OpenC2 responses returned in the HTTP response. 

**EDITOR'S NOTE:** Need to define the convention for a Producer to "check in" with the Consumer later when the response isn’t immediately available.

![no alt title](image_1.png)

**Figure 1 -- OpenC2 Consumer as HTTP Server**

## 2.3 OpenC2 Producer as HTTP server
Figure 2 illustrates the configuration where the OpenC2 Producer operates an HTTP server listening on port pPROD. In this configuration, a Consumer that has been configured to request and accept OpenC2 commands from a particular Producer initiates a TCP connection to the Producer on pPROD. Once the TCP connection is created, a TLS session is initiated to authenticate the endpoints and provide connection confidentiality. In this configuration, the exchange of OpenC2 commands and responses is driven by the Consumer repeatedly polling the Producer.

**EDITOR'S NOTE:** Is it worth a version or variant. when the Producer has no command or query to send?

![no alt title](image_2.png)

**Figure 2 -- OpenC2 Producer as HTTP Server**

## 2.4 Producer and Consumer as HTTP/TLS Listeners
The configuration where both Producer and Consumer operate an HTTP server is operationally similar to the configuration where only the Consumer operates an HTTP server.  In this configuration, a Producer that needs to send OpenC2 commands initiates a TCP connection to the Consumer on pCONS. Once the TCP connection is created, a TLS session is initiated to authenticate the endpoints and provide connection confidentiality. The Producer can then directly issue OpenC2 commands using the HTTP POST method, with Consumer OpenC2 responses returned in the HTTP response. 

In situations where the Consumer needs to send the Producer an OpenC2 response with updated status, it initiates a TCP connection to the Producer on pPROD. Once the TCP connection is created, a TLS session is initiated to authenticate the endpoints and provide connection confidentiality. The Consumer can then transmit OpenC2 response messages using the HTTP POST method.

# 3 PROTOCOL MAPPINGS
The section defines the requirements for using HTTP and TLS with OpenC2, including general requirements and protocol mappings for the three operating configurations described in Section 2.

## 3.1 	Layering Overview
When using HTTPS for OpenC2 message transfer, the layering model is:

| Layer | Description |
|:---|:---|
| OpenC2 Message | The OpenC2 Language Specification defines the overall OpenC2 language and message formats, and the Actuator Profiles implemented by any particular endpoint scope the OpenC2 actions, targets, arguments, and specifiers that apply when commanding that type of Actuator.  |
| Serialization | Serialization converts internal representations of OpenC2 messages into a form that can be transmitted and received. The OpenC2 default serialization is JSON. |
| HTTP | The HTTP layer is responsible for conveying OpenC2 messages and responses, as described in this specification. |
| TLS | The TLS layer is responsible for authentication of connection endpoints and confidentiality and integrity of transferred messages.  |
| Lower Layer Transport | The lower protocol layers are responsible for end-to-end delivery of messages. TCP/IP is the most common suite of lower layer protocols used with HTTPS. |

## 3.2 General Requirements
This section defines serialization, HTTP, and TLS requirements that apply regardless of operating model.

### _3.2.1 Serialization_
While the OpenC2 language is agnostic of serialization, when transferring OpenC2 messages over HTTP/TLS, the default JSON serialization described in the language specification is used.

**EDITOR'S NOTE:** We could define content types for other serializations if there’s demand.

### _3.2.2 __HTTP Usage_
OpenC2 endpoints MUST implement all REQUIRED functionality for HTTP/1.1 ([RFC7230], _et. al._). The only HTTP request methods supported are GET and POST. All OpenC2 messages sent in HTTP Requests MUST be sent using a Request-URI of '/openc2'. 

In this implementation, the default JSON serialization is used, so the content type is 'application/openc2+json; version=1.0'; i.e., the 'Content-type' Request and Response headers MUST be 'application/openc2+json; version=1.0'.

### _3.2.3 TLS Usage_
OpenC2 endpoints MUST use TLS version 1.1 [RFC4346] or higher for confidentiality, identification, and authentication when sending OpenC2 messages over HTTPS.  HTTPS is specified in Section 2 of [RFC2818]. 

The TLS session MUST use non-NULL ciphersuites for authentication, integrity, and confidentiality.  Sessions MAY be renegotiated within these constraints.

OpenC2 endpoints MUST support TLS version 1.1 and SHOULD support TLS version 1.2 [RFC5246]; OpenC2 endpoints MUST NOT request, offer, or use any version of SSL, or any version of TLS prior to 1.1, due to known security vulnerabilities in prior versions of the protocol; see Appendix E of [RFC5246] for more information.

#### 3.2.3.1 TLS Authentication
When deployed in an operational environment, OpenC2 endpoints MUST use mutual authentication; that is, both OpenC2 endpoints acting as HTTPS clients and OpenC2 endpoints acting as HTTPS servers MUST be identified by an X.509 certificate [RFC5280].  Mutual authentication requires full path validation on each certificate, as defined in [RFC5280].

#### 3.2.3.2 TLS Confidentiality
TBD

**EDITOR'S NOTE:** Probably need something about minimum cipher suite. The [KMIP Profiles document](http://docs.oasis-open.org/kmip/profiles/v1.4/os/kmip-profiles-v1.4-os.html) (section 3) has a short (2 item) list of SHALL implement cipher suites, and a much longer list of MAY implement cipher suites. Seems more effective to spec a minimum strength cipher suite for OC2, and say that or anything stronger is acceptable, and let normal TLS negotiation handle it from there.

## 3.3 OpenC2 Consumer as HTTP/TLS Server
This section defines HTTP and TLS requirements that apply when the OpenC2 consumer is the HTTP server.

### _3.3.1 HTTP Usage_
When the OpenC2 Consumer is the HTTP server, the Producer is able to initiate a connection to a specific Consumer and directly transmit OpenC2 messages containing commands; the HTTP POST method is used, with the OpenC2 message contained in the POST body.

The following HTTP request headers MUST be populated when transferring OpenC2 messages:

	

* Host:  <host name of HTTP server>:<listening port number>
* Content-type:  application/openc2+json; version=1.0
* Date:  <date-time> in HTTP-date format as defined by RFC 7231

	

The following HTTP response headers MUST be populated when transferring OpenC2 responses:

	

* Date: <date-time> in HTTP-date format as defined by RFC 7231
* Content-type: application/openc2+json; version=1.0

Example messages can be found in Appendix D, section D.1.

### _3.3.2 TLS Usage_
**EDITOR'S NOTE:**  Any TLS specifics because the Consumer is the listener?

## 3.4 OpenC2 Producer as HTTP/TLS Server
This section defines HTTP and TLS requirements that apply when the OpenC2 Producer is the HTTP server.

### _3.4.1 HTTP Usage_
When the OpenC2 Producer is the HTTP server, the Consumer must poll for commands.  The Consumer checks for commands by polling the Producer with the HTTP GET method. The polling interval is a matter of Consumer configuration but SHOULD be no longer than 60 seconds. Since OpenC2 responses may not always be available immediately, the Producer may be in any of four states with respect to a particular Consumer when that Consumer polls:

    * Producer has no commands and no status queries
    * Producer has commands but no status queries
    * Producer has status queries but no commands
    * Producer has neither commands nor status queries

The intent is that the Producer is able to transmit all commands and status queries to the Consumer in a sequence of exchanges. To accomplish this, the Consumer MUST poll the Producer repeatedly until it receives an HTTP response with code 204, No Content. The Producer will respond to each GET request with an HTTP response with code 200, OK, and a single command or status query in the response body, until the Producer's set of commands and queries is exhausted. The order in which the Producer sends multiple commands and/or status queries is undefined.

**EDITOR'S NOTE:** Need to get agreement on this convention for processing commands and queries, and indicating completion. _If we agree on using status code 204, No Content, that code will need to be added to the Language Spec._

The following HTTP request headers MUST be populated when transferring OpenC2 messages:

	

* Host:  <host name of HTTP server>:<listening port number>
* Content-type:  application/openc2+json; version=1.0
* Date:  <date-time> in HTTP-date format as defined by RFC 7231

	

The following HTTP response headers MUST be populated when transferring OpenC2 responses:

	

* Date: <date-time> in HTTP-date format as defined by RFC 7231
* Content-type: application/openc2+json; version=1.0

Example messages can be found in Appendix D, section D.2.

### _3.4.2 TLS Usage_
**EDITOR'S NOTE:**  Any TLS specifics because the Producer is the listener?

## 3.5 4.5	OpenC2 Producer and Consumer as HTTP/TLS Servers
When both the Producer and Consumer act as HTTP server, the Producer contacts the Consumer to send commands and status queries as described in Section 3.4. If the Consumer needs to send an OpenC2 response to the Producer asynchronously, it uses the process described in Section 3.3, initiating the connection and using the HTTP POST method to send the OpenC2 response message.

Example messages for Producers sending OpenC2 commands can be found in Appendix D, section D.1. Example messages for Consumers asynchronously posting response messages can be found in Appendix D, section D.2.

### _3.5.1 HTTP Usage_
TBD

### _3.5.2 TLS Usage_
TBD

## 3.6 OpenC2 Producer as HTTP/TLS Server
This section defines HTTP and TLS requirements that apply when the OpenC2 Producer is the HTTP server.

### _3.6.1 HTTP Usage_
When the OpenC2 Producer is the HTTP server, the Consumer must poll for commands.  The Consumer checks for commands by polling the Producer with the HTTP GET method. The polling interval is a matter of Consumer configuration but SHOULD be no longer than 60 seconds. Since OpenC2 responses may not always be available immediately, the Producer may be in any of four states with respect to a particular Consumer when that Consumer polls:

    * Producer has no commands and no status queries
    * Producer has commands but no status queries
    * Producer has status queries but no commands
    * Producer has neither commands nor status queries

The intent is that the Producer is able to transmit all commands and status queries to the Consumer in a sequence of exchanges. To accomplish this, the Consumer MUST poll the Producer repeatedly until it receives an HTTP response with code 204, No Content. The Producer will respond to each GET request with an HTTP response with code 200, OK, and a single command or status query in the response body, until the Producer's set of commands and queries is exhausted. The order in which the Producer sends multiple commands and/or status queries is undefined.

**EDITOR'S NOTE:** Need to get agreement on this convention for processing commands and queries, and indicating completion. _If we agree on using status code 204, No Content, that code will need to be added to the Language Spec._

The following HTTP request headers MUST be populated when transferring OpenC2 messages:

	

* Host:  <host name of HTTP server>:<listening port number>
* Content-type:  application/openc2+json; version=1.0
* Date:  <date-time> in HTTP-date format as defined by RFC 7231

	

The following HTTP response headers MUST be populated when transferring OpenC2 responses:

	

* Date: <date-time> in HTTP-date format as defined by RFC 7231
* Content-type: application/openc2+json; version=1.0

Example messages can be found in Appendix D.

### _3.6.2 TLS Usage_
**EDITOR'S NOTE:**  Any TLS specifics because the Producer is the listener?

## 3.7 	Lower Layer Transport
Port Assignment (TBD)

**EDITOR'S NOTE:** Need to request a pair of port assignments from IANA to support this.	

# 4 CONFORMANCE
> **Note to Editor**: The [OASIS TC Process](https://www.oasis-open.org/policies-guidelines/tc-process#wpComponentsConfClause) requires that a specification approved by the TC at the Committee Specification Public Review Draft, Committee Specification or OASIS Standard level must include a separate section, listing a set of numbered conformance clauses, to which any implementation of the specification must adhere in order to claim conformance to the specification (or any optional portion thereof). This is done by listing the conformance clauses here. For the definition of "conformance clause," see [OASIS Defined Terms](https://www.oasis-open.org/policies-guidelines/oasis-defined-terms-2017-05-26#dConformanceClause).
> 
> See "Guidelines to Writing Conformance Clauses":  [http://docs.oasis-open.org/templates/TCHandbook/ConformanceGuidelines.html](http://docs.oasis-open.org/templates/TCHandbook/ConformanceGuidelines.html).
> 
> Remove this note before submitting for publication.

# Appendix A. Acknowledgments
The following individuals have participated in the creation of this specification and are gratefully acknowledged:

**Participants**:

# Appendix B. Revision History
| Revision | Date | Editor | Changes Made |
|:---|:---|:---|:---|
| v1.0-wd01 | 6/15/2018 | Lemire | Initial working draft |

# Appendix C. Acronyms
# Appendix D. Examples
OpenC2 commands and responses need to be transmitted with certain relevant head information (i.e., metadata), as described in Section 3.2 of [OpenC2-Lang-v1.0]. When sending OpenC2 commands and responses over HTTP/TLS, the OpenC2 message head metadata items of created, sender, version, content-type and command-id are handled by the following HTTP header fields:

| OpenC2 Language Element |  HTTP Header |
|:---|:---|
| created | Date |
| sender | From |
| content-type + version | content-type |
| command id | X-Correlation-ID |

The Request-URI /openc2 is used in all HTTP requests.

## D.1 HTTP Request / Response Examples: Consumer as HTTP Server
This section presents the HTTP message structures used when the OpenC2 Consumer acts as the HTTP listener.

### D.1.1 Producer HTTP POST with OpenC2 Command
Example message:

POST /openc2 HTTP/1.1

Host: oc2consumer.company.net

From: oc2producer@company.net

Content-type: application/openc2+json; version=1.0

Date: Day, DD Mon YYYY HH:MM:SS GMT

X-Correlation-ID: shq5x2dmgayf

{	"command": {

		"action": ...

		"target": ...

		"actuator": ...

		"args": ...

	}

}

### D.1.2 Consumer HTTP Response with OpenC2 Response
Example message:

HTTP/1.1 200 OK

Date: Day, DD Mon YYYY HH:MM:SS GMT

Content-type: application/openc2+json; version=1.0

X-Correlation-ID: shq5x2dmgayf

{	"response": {

		"Id_ref": ...

		"status": 200

		"status_text": ...

		"results": { ...

	}

}

## D.2 HTTP Request / Response Examples: Producer as HTTP Server
This section presents the HTTP message structures used when the OpenC2 Producer acts as the HTTP listener.

### D.2.1 Consumer Polls Producer with HTTP GET
Consumers use the HTTP GET method to poll a Producer for available commands and status queries. No message body is required.

GET /openc2 HTTP/1.1

Host: oc2producer.company.net

From: oc2consumer@company.net

Content-type: application/openc2+json; version=1.0

Date: Day, DD Mon YYYY HH:MM:SS GMT

X-Correlation-ID: bf5t2ttrsc8r

### D.2.2 Producer HTTP Response with OpenC2 Command
If the Producer has commands for the Consumer, the Producer returns HTTP 200, Success and places an OpenC2 message with a command body in the body of the HTTP response. This signals the Consumer to process the command, send an HTTP POST with its OpenC2 response message, and then poll again for additional messages from the Producer.

HTTP/1.1 200 OK

Date: Day, DD Mon YYYY HH:MM:SS GMT

X-Correlation-ID: bf5t2ttrsc8r

Content-type: application/openc2+json; version=1.0

{	"command": {

		"action": ...

		"target": ...

		"actuator": ...

		"args": ...

	}

}

### D.2.3 Producer HTTP Response with OpenC2 Status Query
If the Producer has status queries for the Consumer, the Producer returns HTTP 200, Success and places an OpenC2 message with a command to query status in the body of the HTTP response. The id in the OpenC2 message header identifies the command for which updated status is requested. This signals the Consumer to process the status query, send an HTTP POST with its OpenC2 response message, and then poll again for additional messages from the Producer.

HTTP/1.1 200 OK

Date: Day, DD Mon YYYY HH:MM:SS GMT

Content-type: application/openc2+json; version=1.0

X-Correlation-ID: bf5t2ttrsc8r

{	"command": {

		"action": "query"

		"target": "command"

	}

}

### D.2.4 Producer HTTP Response with No Content
If the Producer has no commands or status queries for the Consumer, the Producer returns HTTP 204, No Content. This signals the Consumer to return to its default polling interval.

HTTP/1.1 204 OK

Date: Day, DD Mon YYYY HH:MM:SS GMT

Content-type: application/openc2+json; version=1.0

X-Correlation-ID: bf5t2ttrsc8r

### D.2.5 Consumer HTTP POST with OpenC2 Response
Consumers use the HTTP POST method to send OpenC2 response messages to the Producer.

POST /openc2 HTTP/1.1

Host: oc2producer.company.net

From: oc2consumer@company.net

Content-type: application/openc2+json; version=1.0

Date: Day, DD Mon YYYY HH:MM:SS GMT

X-Correlation-ID: bf5t2ttrsc8r

{	"response": {

		"Id_ref": ...

		"status": 200

		"status_text": ...

		"results": { ...

	}

}

