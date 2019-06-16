# Content References

A key goal for the Topica Information System is to allow easy referencing
from any text to another in a structured fashion. Topica stores key
information about texts (authorship, time of publication etc.) in a
standardized format. Topica content references provide cryptographic
guarantees that the referenced text has not been tampered with, even
when it is retrieved from an untrusted source.

## Direct References (by hash)

Any text stored in the Topica Information System can be referred to
directly with a self-certifying reference. This type of reference refers
to a piece of text exactly as it is at the time the reference is created.
The reference is only valid for the exact version of the text referred to.

Direct references contain a cryptographic signature of the referred content
directly in the reference itself, thus making it possible to verify
the authenticity of the text without access to anything beyond the
reference and the text itself.
