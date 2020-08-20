[![PDF-Preview](https://img.shields.io/badge/PDF-Preview-blue)](https://github.com/ivoa-std/ConeSearch/releases/download/auto-pdf-preview/ConeSearch-draft.pdf)

# Simple Cone Search

This specification defines a simple query protocol, named Simple Cone
Search, for retrieving records from a catalog of astronomical sources.
The query describes a sky position and an angular distance, defining a
cone on the sky. The response returns a list of astronomical sources
from the catalog whose positions lie within the cone, formatted as a
VOTable. 

The current version aims essentially at aligning this specification with
the Data Access Layer (DAL) landscape at the time of writing.

It also currently includes addition of a feature to allow for filtering 
in a specific time window.

Keep in mind to use the --recurse-submodules option when cloning the
repository.

## Document Status 

### Working Document

This specification is currently under revision to reach version 1.1.

A [PDF preview](https://github.com/ivoa-std/ConeSearch/releases/download/auto-pdf-preview/ConeSearch-draft.pdf
"PRE-RELEASE, DO NOT PUBLISH") of the document is automatically generated by a GitHub 
workflow and available
[here](https://github.com/ivoa-std/ConeSearch/releases/download/auto-pdf-preview/ConeSearch-draft.pdf
"PRE-RELEASE, DO NOT PUBLISH") or clicking on the badge on top.

### Latest Stable

The current IVOA Recommendation is: 
[REC-1.03](http://ivoa.net/documents/latest/ConeSearch.html).

The release available in this repo tagged with the same version number 
is a re-styled document that keeps the same content and was prepared 
while porting the HTML version to a LaTeX one in view of a minor revision. 
The originating HTML is available from the 
[official IVOA Document Repository](http://ivoa.net/documents/latest/ConeSearch.html).

## License 

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
<img alt="Creative Commons License" style="border-width:0"
src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a> <br />
This work is licensed under a <a rel="license"
href="http://creativecommons.org/licenses/by-sa/4.0/"> Creative Commons
Attribution-ShareAlike 4.0 International License</a>.
  
