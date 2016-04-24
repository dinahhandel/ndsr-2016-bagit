# VALIDATE AND CHECK BAG COMPLETENESS

Instructions for validating an existing bag with the BagIt Python build.

## WHAT DOES 'VALIDATION' AND 'COMPLETENESS' MEAN?

From the [BagIt spec](https://tools.ietf.org/html/draft-kunze-bagit-13#section-3),

**A _complete_ bag** MUST have the following attributes:
   1.  Every required element MUST be present.
   2.  Every file in every payload manifest MUST be present.
   3.  Every file in every tag manifest MUST be present.  Tag files not listed in a tag manifest MAY be present.
   4.  Every payload file MUST be listed in at least one manifest. Payload files MAY be listed in more than one payload manifest.
   5.  Every element present MUST comply with this specification.

**A _valid_ bag** MUST have the following attributes:

   1.  The bag MUST be complete.
   2.  Every CHECKSUM in every payload manifest and tag manifest can be sucessfully verified against the contents of its corresponding FILENAME.

   Tag files that do not appear in a tag manifest can be modified, added to, or removed from a bag without impacting the completeness or validity of the bag.

## VALIDATING A BAG
1. In Terminal, enter this command:
        `bagit.py --validate [drag and drop existing bag]`


