# Apache MINA (apache-mina)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Apache MINA is a network application framework that helps develop high-performance and high-scalability network applications. It provides an abstract event-driven asynchronous API over various transports such as TCP/IP and UDP/IP via Java NIO. MINA includes sub-projects for SSH (SSHD), FTP (FtpServer), and XMPP (Vysper) protocols.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-mina/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Async I/O, Java, Networking, NIO, Protocol Framework, SSH

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache MINA Core
MINA Core provides a Java NIO-based API for building high-performance network applications with support for TCP and UDP protocols, an event-driven filter chain for protocol codecs, session management, and both client and server roles. Current version is 2.2.5.

**Human URL:** [https://mina.apache.org/mina-project/documentation.html](https://mina.apache.org/mina-project/documentation.html)

#### Tags:

 - Java, NIO, Networking, TCP, UDP

#### Properties

- [Documentation](https://mina.apache.org/mina-project/documentation.html)
- [GettingStarted](https://mina.apache.org/mina-project/userguide/user-guide-toc.html)
- [Maven Central (Java)](https://central.sonatype.com/artifact/org.apache.mina/mina-core)
- [GitHubRepository](https://github.com/apache/mina)

### Apache MINA SSHD
Apache MINA SSHD is a comprehensive Java library for client- and server-side SSH protocol implementation. It supports SCP, SFTP, port forwarding, key management, and various authentication methods. Current version is 2.17.1.

**Human URL:** [https://mina.apache.org/sshd-project/index.html](https://mina.apache.org/sshd-project/index.html)

#### Tags:

 - Java, Security, SCP, SFTP, SSH

#### Properties

- [Documentation](https://mina.apache.org/sshd-project/index.html)
- [Maven Central (Java)](https://central.sonatype.com/artifact/org.apache.sshd/sshd-core)
- [GitHubRepository](https://github.com/apache/mina-sshd)

### Apache FtpServer
Apache FtpServer is a 100% pure Java FTP server built on MINA. It is designed to be used as a complete and portable FTP server engine solution based on currently available open protocols. Current version is 1.2.1.

**Human URL:** [https://mina.apache.org/ftpserver-project/index.html](https://mina.apache.org/ftpserver-project/index.html)

#### Tags:

 - FTP, Java, Server

#### Properties

- [Documentation](https://mina.apache.org/ftpserver-project/index.html)
- [Maven Central (Java)](https://central.sonatype.com/artifact/org.apache.ftpserver/ftpserver-core)
- [GitHubRepository](https://github.com/apache/mina)

## Common Properties

- [Portal](https://mina.apache.org/)
- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/mina)
- [GitHubRepository](https://github.com/apache/mina-sshd)
- [GitHubRepository](https://github.com/apache/mina-site)
- [IssueTracker](https://issues.apache.org/jira/browse/DIRMINA)
- [MailingList](https://mina.apache.org/mina-project/mailing-lists.html)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)

## Features

| Name | Description |
|------|-------------|
| Event-Driven Architecture | Abstract event-driven asynchronous API enabling high-performance non-blocking I/O network application development. |
| Java NIO Foundation | Built on Java NIO for scalable, non-blocking network I/O supporting thousands of concurrent connections. |
| Filter Chain | Pluggable filter chain architecture for protocol codec, logging, compression, and security processing. |
| Multi-Transport Support | Supports TCP/IP and UDP/IP transports with a unified programming model across both. |
| SSH Client and Server | SSHD sub-project provides full SSH client and server implementation with SCP, SFTP, and port forwarding. |
| FTP Server | FtpServer sub-project provides a complete, embeddable FTP server implementation built on MINA. |
| XMPP Server | Vysper sub-project provides an extensible XMPP server implementation for instant messaging. |
| Session Management | Comprehensive session lifecycle management with configurable timeouts, idle detection, and connection throttling. |

## Use Cases

| Name | Description |
|------|-------------|
| Custom Network Protocol Implementation | Build custom client-server protocols over TCP/UDP using MINA's filter chain and codec framework. |
| SSH Automation and File Transfer | Implement SSH automation, SFTP file transfer, and SCP operations using Apache MINA SSHD. |
| Embedded FTP Server | Embed a fully functional FTP server within Java applications using Apache FtpServer. |
| High-Concurrency Network Services | Build network services handling thousands of concurrent connections with minimal resource usage via NIO. |
| IoT Device Communication | Implement lightweight IoT device communication protocols over TCP/UDP using MINA's framework. |

## Integrations

| Name | Description |
|------|-------------|
| Spring Framework | MINA integrates with the Spring Framework for dependency injection and application lifecycle management. |
| SLF4J and Logback | Native SLF4J logging integration for structured logging across all MINA components. |
| Bouncy Castle | Bouncy Castle cryptography library integration for SSH key management and cryptographic operations in SSHD. |
| Apache Karaf | MINA components can be deployed as OSGi bundles in Apache Karaf container. |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
