# cdif-core
A repository to host the core interoperability specifications for CDIF

There are two top level subdirectories:

**in_review**: hosts proposed templates and guidance documents for different resource types or metadata components.

**adopted**: host templates that have been reviewed and tested by the CDIF working group and are recommended for use.

Subdirectories in these top level directories host templates and guidance documents for particular resource types or metadata components. Each subdirectory has three folders: Examples, Templates, and Validation. Guidance documents (preferably using Markdown) should be in in the root subdirectory for the resource type.

- Examples are valid schema.org JSON-LD documents documenting actual data.

- Templates are typically JSON_LD docs with explanatory text for the content of the keys in the JSON doc. The templates are  serialised in [JSON-LD](https://www.w3.org/TR/json-ld11/) using the [schema.org](https://schema.org/) vocabulary. [JSON Schema](https://json-schema.org/specification) or [SHACL](https://www.w3.org/TR/shacl/)/[SHEX](https://github.com/shexSpec/shex/wiki/ShEx) rule sets might also be provided for validation. 

- Validation folder contains JSON schema, SHACL rule sets or similar docs that can be used to validate JSON-LD following recommendations.


