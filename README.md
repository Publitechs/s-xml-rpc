License: LLGPL
Source: http://common-lisp.net/project/s-xml-rpc/

S-XML-RPC is an implementation of XML-RPC in Common Lisp for both client and server. Originally it was written by Sven Van Caekenberghe. It is now being maintained by Sven Van Caekenberghe, Rudi Schlatte and Brian Mastenbrook. S-XML-RPC is using S-XML as parser.

XML-RPC is a de facto standard for making remote procedure calls between software running on disparate operating systems, running in different environments and implemented using different languages. XML-RPC is using HTTP as the transport and XML as the encoding. XML-RPC is designed to be as simple as possible, while allowing complex data structures to be transmitted, processed and returned. The protocol is described in detail on http://www.xmlrpc.com/. Some key features (both positive and negative) of the XML-RPC protocol are:

* It is a published protocol implemented in a variety of languages and operating systems.
* It allows communication between applications implemented in different languages.
* It allows communication over the internet and through firewalls.
* It is not intended for time-critical communications, or for the transmission of large volumes of data.
* It is an asymmetrical protocol allowing calls from the client to the server but not callbacks from the server to the client.
* It is a very simple protocol that it not defined, controlled or endorsed by a standards body.
* It works.

*Moved to Github by Ilya Khaprov <mail@publitechs.com>*
