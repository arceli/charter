# Arceli

## An archive of informal astronomy communications

Arceli was created in recognition that the Internet allows astronomers to publish useful material outside of traditional journals, yet there is no effective mechanism for these communications to be archived, indexed and cited (see [this Twitter conversation](https://storify.com/aaccomazzi/non-traditional-citations-in-astronomy) for Arceli's genesis).
Arceli acts as a facilitator for archiving communications on behalf of authors and providing a structure that NASA/SAO ADS can index.

This is a working document that specifies the vision for Arceli and how the project funcitons.

## Overview

- Arceli is an archive of informal astronomy communications;
    * Arceli is partnered with the CfA Library, Zenodo, ScienceBetter, and ADS,
    * Arceli is fundamentally a Zenodo curated community,
    * ADS agrees to index the resources of this Zenodo community,
    * [PressForward](http://pressforward.org/) is used to collect and discuss content
    * Online Publishers (such as a blog) apply for affiliation with Arceli.
    * Online publishers are given an account on Arceli in order to allow for self-moderation and community curation.
- The Publisher posts their content to the web as usual. The Publisher retains all rights to their work, but the content must be licensed, either CC0 or CC-by, to allow for archiving.
- Only if the Publisher deems the content to be relevant to scholarly astronomy discourse do they intentionally submit the content to the Zenodo community. This also implies that content can be retroactively submitted.
    * Arceli accepts the submission automatically because the Publisher is affiliated (trusted) and has its own community. This reduces Arceli's operational cost.
    * The Publisher gets a DOI for the content and it is up the Publisher to put this DOI into any online markup.
- ADS indexes Arceli's resources.
- If a Publisher is found to in breach of these guidelines, the Publisher may lose affiliate status and have their articles removed from the Zenodo community and ADS.

![alt text](https://github.com/dbouquin/charter/raw/master/assets/arceli_workflow.png "Arceli workflow")

## Governance

Arceli is under continuous development by a group of professional astronomers, librarians, and software developers. The Project is community-driven, with decisions generally made by consensus, but with oversight and organization provided be two project leads: ScienceBetter (Kelle Cruz) and [CfA Library](https://github.com/CfA-Library). Press Forward, Zenodo, and ADS organization are project partners. The project leads work closely with representatives from the partner organizations to make functional, technical, and financial decisions.

Project contributors are involved in all aspects of the project. Discussions among leads, partners, and contributors are held primarily in the Arceli Project Github organization and everyone affilitated with the project is encouraged to participate in these discussions.

## Moderation

[PressForward](https://github.com/PressForward/pressforward/wiki/User-Manual#using-the-all-content-page-how-to-read-nominate-and-add-comments-to-items) provides the platform for the editors to curate and discuss content.

TBD: who will actually moderate and make final go to publish.

## Topics
### Accepted Topics

Anything relevant to the astronomy community that doesn't have a home elsewhere.

### Not Accepted Topics

Scientific results that could otherwise be published on the arxiv. See discussion in [#6](https://github.com/archive-of-informal-astronomy-comm/charter/issues/6).

## Media
### Accepted Media

We plan to accept:

- blog posts that contain text and images
- ipython or jupyter notebooks which contain explanatory text
- videos - paper summaries, tutorials, etc.
- animations and graphics - visuals which could be of use to wider community
- talk slides - talk slides with relevance to the wider community.

### Not Accepted Media

- pre-print style journal articles that would otherwise go on arxiv.

### Metadata Information
The current metadata crosswalk is accessible [here](https://docs.google.com/spreadsheets/d/1ti2ny9o0_fpA0ZgWe_F6o9ISmBApEjjDRTu0P7XLRd4/edit?usp=sharing).   
Discussion on metadata can be found in the repo issues [here](https://github.com/arceli/charter/issues/24).

### Guidelines for Submission's content and format

It should be easily and openly readable, e.g., plaintext/markdown and images or an ipython or Jupyter notebook.
If appropriate, a PDF rendering is encouraged.
[Something about URL and/or original blog.](https://github.com/archive-of-informal-astronomy-comm/charter/issues/5)

## How ADS indexes Arceli

Pages processed by Arceli will appear like normal articles on ADS. You will see the normal fields filled with helpful data:

- **Title** will be the Blog Post Title
- **Authors** will be the Blog Post Authors
- **Affiliations** will be the Blog Post Author's affiliations, if available
- **Publication** will say	 "BLOG TITLE, Aggregated by Arceli"
- **Publication Date** will be the blog post published date, not the Arceli archive date.
- **DOI** will be filled in with the Zenodo-generated DOI
- **bibstem** (the first part of the **Bibliographic Code**) will be `2016arcel..etc`
