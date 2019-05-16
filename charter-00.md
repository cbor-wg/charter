## Charter for Working Group

Concise Binary Object Representation (CBOR, RFC 7049) extends the
JavaScript Object Notation (JSON, RFC 7159) data interchange format to
include binary data and an extensibility model, using a binary
representation format that is easy to parse correctly. It has been
picked up by a number of IETF efforts (e.g., CORE, ANIMA GRASP) as a
message format.

The CBOR working group will update RFC 7049 to fix verified errata.
Security issues and clarifications may be addressed, but changes to the
document will ensure backward compatibility for popular deployed
codebases. The resulting document will be targeted at becoming an
Internet Standard.

Similar to the way ABNF (RFC 5234/7405) can be used to describe the set
of valid messages in a text representation, it would be useful if
protocol specifications could use a description format for the data in
CBOR-encoded messages. The CBOR data definition language (CDDL, based on
draft-greevenbosch-appsawg-cbor-cddl) is a proposal for such a
description technique that has already been used in CORE, ANIMA, CDNI,
and efforts outside the IETF. The CBOR WG will complete the development
of this specification by creating an Informational or Standards Track
RFC. The document should specify its applicability statement in
relationship to YANG data modelling language.

In parallel to the work on CDDL, the WG will examine the CBOR extension
for tagging of Typed Arrays (based on draft-jroatch-cbor-tags) and the
CBOR extension for tagging of Object Identifiers and UUIDs (based on
draft-bormann-cbor-tags-oid) that use CBOR's extensibility mechanisms to
provide additional data types as used in certain applications. Where
these proposals are deemed useful and do not require significant new
development, the CBOR WG will complete these specifications as well. The
WG will recharter before working on any further CBOR extensions.
