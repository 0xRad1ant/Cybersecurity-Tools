# fping

## What is fping?

**fping** is a network diagnostic tool designed to send ICMP echo probes to network hosts, similar to the traditional 'ping' command. However, fping excels in performance, especially when pinging multiple hosts concurrently. With its origins dating back to 1992, fping has established itself as a standard tool for network diagnostics and statistical analysis.

## Announcing Version 3

The development of fping saw a significant gap between official releases from 2002 until the end of 2011. During this period, various patches existed but were never integrated upstream. Due to the absence of the official maintainer's response to emails, the responsibility of maintenance was taken over by a new maintainer.

Version 3 marked a change in maintenance and performance enhancements. Notably, the main loop implementation underwent a complete rewrite, resulting in substantial performance improvements. The runtime of fping is now closer to the theoretical time required to send and receive pings under specified parameters.

### Changes in fping 3.0:

- Integration of Debian patches up to version 2.4b2-to-ipv6-16.1
- Modifications by Tobias Oetiker for SmokePing (2.4b2-to4)
- Reimplementation of the main loop for improved performance

For further details, refer to the latest ChangeLog file.

## Download and Release Information

- **Latest Source:** [fping 5.1 (release notes)](https://fping.org/dist/)
- Download release source distributions or the latest sources from [GitHub](https://fping.org/dist/).

Binaries are available for various platforms, though they are not directly downloadable from the website. Notably, distributions like Debian, Gentoo, and Archlinux offer fping in their latest versions.

## Official Links

- **[fping Website](https://fping.org/):** Explore the official website for detailed information about fping and its capabilities.
- **[fping Download Page](https://fping.org/dist/):** Access the download page to obtain the release source distributions or the latest sources from GitHub.

fping continues to be a powerful and efficient network diagnostic tool, offering enhanced performance and functionality for diagnosing network connectivity and assessing host responsiveness.
