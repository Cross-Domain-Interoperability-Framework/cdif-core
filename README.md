# cdif-core
A repository to host the core interoperability specifications for CDIF


Subdirectories in these top level directories host templates, examples, and guidance documents for particular resource types or metadata components. Each subdirectory has three folders: Examples, Templates, and Validation. Guidance documents (preferably using Markdown) should be in in the root subdirectory for the resource type.

- Examples are valid schema.org JSON-LD that document actual data.

- Templates are typically JSON_LD docs with explanatory text for the content of the keys in the JSON doc. The templates are  serialised in [JSON-LD](https://www.w3.org/TR/json-ld11/) using the [schema.org](https://schema.org/) vocabulary. 

- Validation folder contains [JSON Schema](https://json-schema.org/specification), [SHACL](https://www.w3.org/TR/shacl/)/[SHEX](https://github.com/shexSpec/shex/wiki/ShEx) rule sets or other artifacts provided to validate JSON-LD following recommendations.

Workflow:
to contribute, you'll need to 
- create (or identify an existing) issue that explains the need for an update
- fork this repo (or create a branch if you have permission) and make updates. 
- When things look good in your updated version, create a pull request to bring the revisions into the main branch (if you're in a fork, it will be upstream/main), referencing the issue as background.
- Request review from appropriate team members
- Please restrict updates in a pull request to content in a single resource or component folder (might affect any of the guidance doc, examples, validation scripts, schema...)
- after review, the CDIF team will pull the updates
- if all is good, delete the branch where the updates were created to avoid clutter
- celebrate the march of progress!



