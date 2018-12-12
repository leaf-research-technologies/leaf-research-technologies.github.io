---
layout: post
title:  "Dog Biscuits now on rubygems.org"
date:   2018-12-12 09:28:00 +0100
categories: samvera
---
[Dog Biscuits](https://github.com/samvera-labs/dog_biscuits) is a ruby gem that provides a set of re-usable models, or work types, for use in Hyrax applications.

Dog Biscuits was created and is maintained by [Julie Allinson](https://github.com/geekscruff) from the Research Technologies Team, CoSector, University of London. Originally started whilst working at the University of York, the motivation for DogB iscuits was the need to re-use models across different applications, and also Hyrax' limited in-built support for metadata, and the many steps required to configure new metadata properties in a Hyrax application.

Towards the end of 2017, the code was made a community gem and moved into the Samvera Labs GitHub organization to promote greater community use and contribution. In Decmeber 2018, a significant refactor made the gem much more streamlined and easier to configure. At that point we decided to release the gem on [rubygems](https://rubygems.org/gems/dog_biscuits).org - the Ruby community's gem hosting service.

Key Features of Dog Biscuits:

- Models for authority records and services for using those with the questioning_authority service;
- Models for a number of common work types:
  - Conference Item
  - Dataset
  - Digital Archival Object
  - Exam Paper
  - Journal Article
  - Package (eg. an AIP, DIP or SIP)
  - Published Work
  - Thesis
- New templates for form fields, including:
  - funder - use the crossref fundref autosuggest service
  - part_of - for JournalArticle use the crossref journals autosuggest service
  - publication_status - use a file_based authority
  - refereeed - show radio buttons for Yes and No
  - resource_type_general - use a file_based authority (from config/authorities)
- Configurable support for using a date picker in date form fields (using `bootstrap-datepicker`)
- Configurable support for adding a date range filter into the search (with `blacklight_range_limit`)
- Lots of configuration options for works (property set, property order, labels, help text and more)

To find out more, please see the [Dog Biscuits GitHub repository](https://github.com/samvera-labs/dog_biscuits) and the [Dog Biscuits wiki](https://github.com/samvera-labs/dog_biscuits/wiki). 

We really do want Dog Biscuits to be useful to the community and would be delighted to have tire kickers and code contributors. Please feel free to create [issues](https://github.com/samvera-labs/dog_biscuits/issues) or ping `julieallinson` on samvera slack. 

For infromation about the Research Technologies Team, or our services, please see: [http://www.cosector.com/research-technologies]
