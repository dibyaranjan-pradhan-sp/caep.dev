# caep.dev Libraries

## [secevent](./secevent)
A comprehensive Go library for building, signing, parsing, and validating Security Event Tokens (SecEvents) according to the Security Event Token [RFC 8417](https://tools.ietf.org/html/rfc8417).

**Note:** This fork has been modified to enhance the SET token parsing capabilities to meet specific internal project requirements (e.g., support for additional claims, custom validation logic). These changes are intended as temporary patches until upstream merges the requested changes.

## Issue Created:
[ Caep Issue-63 ](https://github.com/SGNL-ai/caep.dev/issues/63)

## Contributing

Contributions to the project are welcome, including feature enhancements, bug fixes, and documentation improvements.

**Important:** When contributing to `secevent`, please note that this fork contains custom parser enhancements. Make sure to preserve or clearly document any changes related to Token parsing.