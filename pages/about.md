---
# See project.yml for variables.
---
## Overview

Building community around and gathering knowledge about the world’s earwigs.

The _{{ app:project_name }}_ file offers a community-curated collection of richly-cited and annotated information on the taxonomy of Earth’s {{app:focal_taxon_common_name}}. Data found here come from a collaboratively compiled database originating in an instance of [TaxonWorks](https://taxonworks.org) managed by the [Species File Group](https://speciesfilegroup.org). This site is built using TaxonPages, learn more [here](https://github.com/SpeciesFileGroup/taxonpages). These pages are built with open-source software; read more [here](http://speciesfilegroup.org/docs/taxonworks_in_production_at_sfg.html) about what drives them and how they are supported by the Species File Group and their many collaborators. To get further involved join weekly support meetings [here](https://speciesfilegroup.org/events.html).

## Project development and maintenance

|name|role|
|----|----|
| Heidi Hopkins | Lead Curator |
| Boris Eliseev | Assistant Curator |
| Stephan Kleinfelder | Data Contributor |
| Michael D. Maehr\* | Founding Curator |
| Fabian Haas\* | Data Contributor |
| Lesley S. Deem\* | Editor |
| David C. Eades\* | Founding Developer |

_\* Past contributor, now inactive._

- **Cite** this website: Hopkins, H., Eliseev, B., Kleinfelder, S. & Eades, D.C.  Dermaptera Species File. [retrieval date]. <https://dermaptera.speciesfile.org>. See also [Terms of use](#terms-of-use).

### Contribute or get help
The Earth's biodiversity is vast and the data captured to describe it, while minimal in comparison, are still immense. All projects of this nature contain gaps and errors, and contributions and corrections from users are always welcome. Known gaps in this project may include an incomplete catalog of type-material, lack of species depictions, missing biological associations, incomplete distribution records, and incomplete taxonomic/publication histories. <TrackerReport label="Report a problem, offer data, or get involved" tag="a" button-class="cursor-pointer" /> on our issue tracker if you would like to help us address these or other gaps in the data, or if you find a bug.

### Extended data access
A goal of these pages is to ensure that the underlying data behind them are accessible in their digital format. By diversifying the ways the data are accessible (e.g. on the web page, in JSON, in Darwin Core standard), we increase the opportunities to both spot errors and provide new services and portals.

- Anyone interested in working on any group of insects contained in this project can obtain tutoring on how to use the rich, multi-faceted TaxonWorks' interfaces (e.g. filters, reporting, downloads). <TrackerReport label="Contact us" tag="a" button-class="cursor-pointer" /> on our issue tracker if you would like to pursue this opportunity.
- Data behind individual panels per page can be seen via the _Sitemap_ functionality.
- Each page offers an option to download a _DarwinCore formatted table_ containing all data for this taxon and its children.
- Panel data (each section on a page) and other information not available on these pages are accessible via a [TaxonWorks API](https://api.taxonworks.org) at [https://sfg.taxonworks.org/api/v1](https://sfg.taxonworks.org/api/v1).
- Core taxonomic data are exported to and available at the [Catalogue of Life](https://www.catalogueoflife.org/data/dataset/1158).

## History

As of August 2023 all data in the former Species File Websites were frozen and shortly thereafter migrated to TaxonWorks. As with all migrations of this nature the process is both lossy (e.g. some data could not be mapped with certainty) and improved (e.g. semantics of the new models have more precision and clarity). The old website remains an excellent resource for fact-checking this migration and is available at [http://{{app:focal_taxon}}.archive.speciesfile.org](http://{{app:focal_taxon}}.archive.speciesfile.org).

## Support and funding

This Species File functionality and content is serviced in part by the Species File Group.

## Terms of use
<div class="flex items-center gap-2">
  <a
    class="min-w-fit"
    href="{{ app:copyright_image_link }}"
  >
    <img 
      src="{{ app:copyright_image }}" 
      alt="copyright" 
      class="m-0"
    >
  </a>
  <span>{{ app:copyright_text }}</span>
</div>


