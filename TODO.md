* track for each implementation which version added (or removed) each protocol
* record default order client tries protocols
* record which protocols are disabled / enabled by default
* for impls which are both client and server, some protocols may
  only be supported by one but not the other. support that
* link to specs, or perhaps just
   http://www.openssh.com/specs.html
* note whether its a library, stand-alone client/server, or both
* record more features? e.g. SCP/SFTP support, ...
* mention SSH v1 support (I guess not supporting it could be counted as a 
  feature these days... or at least it is important that one can disable it)

For the table with the protocol specifications:
* record for each protocol where it is described (RFC, etc.),
* also: whether it is required / recommended / optional / not listed in the RFC
* whether is deemed unsafe (with link(s) to substantiate that)


Add more implementations! Some lists:
* https://en.wikipedia.org/wiki/Comparison_of_SSH_clients
* https://en.wikipedia.org/wiki/Comparison_of_SSH_servers