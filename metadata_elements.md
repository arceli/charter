<!--- Removed from Charter README -->
### REST Metadata Guidelines

Zenodo's [REST API specifies metadata](https://zenodo.org/dev#restapi-rep-meta) that can be included with a submission. This section provides some guidelines on how these fields should be used.

- `creators`. We mandate that the authors include an `orcid` field to encourage author disambiguation with [ORCID](http://orcid.org). The `affiliation` field is also mandated.
- `title` should match the original title of the work on the web.
- `publication_date` should be the date the work was originally published to the web.
- `description` will be mapped to the work's abstract on ADS. It can be drawn from the original content or be created for the deposition. It cannot be empty.
- `access_right` must be `'open'`. (Does it make sense to allow `closed` or `embargoed`?)
- `license` must be specified.
- `references`. Publishers must strive to properly cite material quoted or linked to through this field.
- `keywords`. Should we mandate a controlled keyword vocabulary?
- `upload_type`. We should allow any of these: `publication`, `poster`, `presentation`, `dataset`, `image`, `video`, `software`.
- `publication_type` if the material is a `publication`, such as a blog post, how do we describe that? `other`? `technicalnote`? `report`?
- `communities` must be the Publisher's own community within Arceli.
- `related_identifiers` should be automatically amended after submission to include the ADS bibcode.
