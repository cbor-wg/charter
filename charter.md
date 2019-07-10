Concise Binary Object Representation (CBOR, RFC 7049) extends the JavaScript
Object Notation (JSON, RFC 8259) data interchange format to include binary
data and an extensibility model, using a binary representation format that
is easy to parse correctly. It has been picked up by a number of IETF
efforts (e.g., CORE, ANIMA GRASP) as a message format.

The CBOR working group will update RFC 7049 to deal with existing errata. Security
issues and clarifications may be addressed, but changes to the document will
ensure backward compatibility for popular deployed codebases. The resulting
document will be targeted at becoming a Internet Standard. After that,
the CBOR working group will monitor issues found with the CBOR specification
and, if needed, will produce an updated document.

Similar to the way ABNF (RFC 5234/7405) can be used to describe the set of
valid messages in a text representation, it is useful for protocol
specifications to use a description format for the data in CBOR-encoded
messages. The Concise Data Definition Language (CDDL) is such a description
technique that has already been used in CORE, ANIMA, CDNI, and efforts
outside the IETF.

CDDL has been published as RFC 8610. While this specification has been
completed, several new features were raised during the update process that
were not included, in order not to delay publication, and to allow
publication in the Standards Track. One example of such a feature is the
ability to combine multiple CDDL files together using a mechanism other than
manually concatenating them together for processing. The working group will
collect these features as well as other features that are raised by users of
CDDL, evaluate their utility and add to a second edition of the
specification as warranted.

The working group will define the approach to further evolving CDDL as a
sequence of editions, which might also add further extension points,
probably as part of the introduction of the next edition of the CDDL base
specification. The body of existing specifications that make use of CDDL is
considered precious, and the WG will set out not to damage their value.

The working group will evaluate the necessity of providing advice and
guidance for developers using CBOR and CDDL. It is currently expected that
this would be done using a Wiki of some type. This work would not be
expected to be published by the IETF.

There are a number of additional CBOR tagged types and CBOR related media type
specifications that are currently
adopted by the working group, are work items in other working groups, or exist as individual
submissions. Additionally, there are expected to be other such documents
that will come to the attention of the working group. In some cases, the
working group expects to adopt and publish these proposals.
The working group will evaluate such proposal individually and decide about 
addition of a respective milestone. Proposals that are deemed to be out of 
scope for the working group, e.g. because they are too narrow purpose 
specifications, may still be published as individual submission or in another 
groups if there is a specific need. The CBOR group will review these proposals 
on request.