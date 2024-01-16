# cdif-core
A repository to host the core interoperability specifications for CDIF that have been adopted:

**adopted**: host templates, examples, validation files that have been reviewed and tested by the CDIF working group and are recommended for use.

Subdirectories in the 'module' directories host templates and guidance documents for particular resource types or metadata components. Each subdirectory has three folders: Examples, Templates, and Validation. Guidance documents (preferably using Markdown) should be in in the root subdirectory for the resource type.

- Examples are valid schema.org JSON-LD documents documenting actual data.

- Templates are typically JSON_LD docs with explanatory text for the content of the keys in the JSON doc. The templates are  serialised in [JSON-LD](https://www.w3.org/TR/json-ld11/) using the [schema.org](https://schema.org/) vocabulary. [JSON Schema](https://json-schema.org/specification) or [SHACL](https://www.w3.org/TR/shacl/)/[SHEX](https://github.com/shexSpec/shex/wiki/ShEx) rule sets might also be provided for validation. 

- Validation folder contains JSON schema, SHACL rule sets or similar docs that can be used to validate JSON-LD following recommendations.


* workflow:

- User makes contribution on the inReview branch for a particular resource type of metadata components
- When the update on the branch is tested and deemed ready for community use, user creates pull request to move inReview commit to adopted (main). [currently this is all in pull request and draft for workflow]
- pull request from inReview to adopted(MAIN) is reviewed and adopted, PR is executed. 



