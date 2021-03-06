greedyMapper
============

A simple program for centralizing distributed [libmapper](http://www.libmapper.org) network topologies.

This program is intended as a proof-of-concept to show that [libmapper](http://www.libmapper.org) can be used in
a centralized client-server-like mode if desired. On startup the program will reroute all existing libmapper
connections on the local network through itself while maintaining all specified signal processing. While running it
will continue to dynamically reroute any new mapping connections, and when terminated it will return the network to
it's previous distributed (peer-to-peer) state.

This software was written in the [Input Devices and Music Interaction
Laboratory](http://www.idmil.org) at McGill University in Montreal, and is copyright those
found in the AUTHORS file.  It is licensed under the GNU Lesser Public
General License version 2.1 or later.  Please see COPYING for details.
