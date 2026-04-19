# Apache MINA (apache-mina)
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
