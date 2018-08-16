Rust WebRTC
======================================================================

Work In Progress
----------------------------------------

This crate is a work in progress.  Current work is focused on the
development of a pure-Rust SCTP implementation for WebRTC data channels
in the webrtc-sctp crate.


Goal
----------------------------------------

The goal is to develop a WebRTC stack that is implemented in pure Rust
as much as possible.


Background
----------------------------------------

Peer-to-peer networking has been used to good effect over the past 20
years to improve services such as audio/video conferencing, online
gaming, and overlay networks, in spite of NAT traversal requiring exotic
techniques and reinventing the universe on top of UDP.  WebRTC is an
IETF standard that bundles together the best-known methods and several
pre-existing standards for peer-to-peer networking to provide a common
target for interoperability.  I think it would be interesting and
educational to develop a full WebRTC stack in Rust as a possible
alternative to the C/C++ reference implementation.  This would not only
provide a second option for application developers, but expand the
ecosystem of network building blocks implemented in a safe programming
language.


License
----------------------------------------

This crate is distributed under the terms of both the MIT license and
the Apache License (Version 2.0).  See LICENSE-MIT and LICENSE-APACHE
for details.

#### Contributing

Unless you explicitly state otherwise, any contribution you
intentionally submit for inclusion in the work, as defined in the
Apache-2.0 license, shall be dual-licensed as above, without any
additional terms or conditions.
