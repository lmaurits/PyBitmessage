About this fork
---------------

I think the BitMessage concept is interesting and worth attention.  However, I
think that the current codebase will give a lot of experienced Python developers
a visceral "yuck!" reaction: global variables, functions and methods hundreds
of lines long, variable names hundreds of characters long, no docstrings, no
package structure, etc, etc.  This is not just an aesthetic thing.  If the code
is scary, it will be hard to attract talented crypto folks to do a proper
security audit to build confidence in the system.  Also, the current written
documentation for the protocol is a little vague on some details, so for now the
reference implementation's code *is* the protocol specification.  As such, it
needs to be easy to read.

This fork is aimed, for now, at restructuring and rewriting the BM code to
improve readability and clarity.  As a nice side-effect, I'll learn more about
the protocol, and maybe squish some bugs along the way.

PyBitmessage
============

Bitmessage is a P2P communications protocol used to send encrypted messages to
another person or to many subscribers. It is decentralized and trustless,
meaning that you need-not inherently trust any entities like root certificate
authorities. It uses strong authentication, which means that the sender of a
message cannot be spoofed, and it aims to hide "non-content" data, like the
sender and receiver of messages, from passive eavesdroppers like those running
warrantless wiretapping programs.


Development
----------
Bitmessage is a collaborative project. You are welcome to submit pull requests 
although if you plan to put a non-trivial amount of work into coding new
features, it is recommended that you first solicit feedback on the DevTalk
pseudo-mailing list:
BM-2D9QKN4teYRvoq2fyzpiftPh9WP9qggtzh


References
----------
* [Project Website](https://bitmessage.org)
* [Protocol Specification](https://bitmessage.org/wiki/Protocol_specification)
* [Whitepaper](https://bitmessage.org/bitmessage.pdf)
* [Installation](https://bitmessage.org/wiki/Compiling_instructions)
