---
# See project.yml for variables.
---
# About
Building community around and gathering knowledge about the world’s earwigs.

## Overview
The _{{ app:project_name }}_ file offers a community-curated collection of richly-cited and annotated information on the taxonomy of Earth’s {{app:focal_taxon_common_name}}. Data found here come from a collaboratively compiled database originating in an instance of [TaxonWorks](https://taxonworks.org) managed by the [Species File Group](https://speciesfilegroup.org). See [Contribute](#contribute-or-get-help) for how you can participate. This site is built using TaxonPages, [learn more and get help](https://github.com/SpeciesFileGroup/taxonpages). For more on how this site is built please see the [Software](#software) section.

## Project development and maintenance

|name|role|
|----|----|
| Heidi Hopkins | Author |
| Fabian Haas | Data Provider |
| Lesley S. Deem | Editor |
| Michael D. Maehr\* | Author |
| David C. Eades\* | Developer |

_\* Past contributor, now inactive._

### Contribute or get help
The Earth's biodiversity is vast, the data captured to describe it are minimal in comparison, but still immense. All projects of this nature contain gaps, i.e. opportunities for collaboration on future work, grants, and research. Known gaps in this project may include an incomplete catalog of type-material, incomplete photographic depictions, missing biological associations, incomplete distribution records, and more. [Contact us](#contribute-or-get-help) if you would like to help us address these or other gaps in the data.

- **<a href="mailto:{{app:contact_email}}">Email</a>** is the primary way to contact us to **provide new data, identify a problem with existing data**, or inquire about **joining** the researchers building this Species File.
- **Cite** this website: Hopkins, H. Hass, F. & Deem, L.S. Dermaptera Species File. [retrieval date]. <https://dermaptera.speciesfile.org>. See also [Terms of use](#terms-of-use).
- If **something is broken** (i.e. with TaxonPages the software) see [Software](#software), or use the [TaxonPages Issue Tracker](https://github.com/SpeciesFileGroup/taxonpages/issues).

### Extended data access
A goal of these pages is to ensure that the underlying data behind them are accessible in their digital format. By diversifying the ways the data are accessible (e.g. on the web page, in JSON, in Darwin Core standard), we increase the opportunities to both spot errors and provide new services and portals.

- Researchers working on this project use their rich, multi-faceted access to the data via TaxonWorks' interfaces (e.g. filters, reporting, downloads). Access requires a project account, see [Contribute or get help](#contribute-or-get-help).
- Data behind individual panels per page can be seen via the _Sitemap_ functionality.
- Each page offers an option to download a _DarwinCore formatted table_ containing all data for this taxon and its children.
- Panel data (each section on a page) and other information not available on these pages are accessible via a [TaxonWorks API](https://api.taxonworks.org) at [https://sfg.taxonworks.org/api/v1](https://sfg.taxonworks.org/api/v1).
- Core taxonomic data are exported to and available at the [Catalogue of Life](https://www.catalogueoflife.org/data/taxon/8MP8D) and its [associated API]({https://link_to_api_for_pertinent_dataset}).

### Software
These pages are built with completely open-source software. [Read more](http://speciesfilegroup.org/docs/taxonworks_in_production_at_sfg.html) about what drives them, how they supported by the Species File Group and their many collaborators, or [join weekly support meetings](https://speciesfilegroup.org/events.html) and see how it all fits together, includes links to issue trackers.

## History
Our former website is now a read-only resource available at [http://{{app:focal_taxon}}.archive.speciesfile.org](https://{{app:focal_taxon}}.archive.speciesfile.org).

As of August 2023 all data in the former Species File Websites were frozen and shortly thereafter migrated to TaxonWorks. As with all migrations of this nature the process is both lossy (e.g. some data could not be mapped with certainty) and improved (e.g. semantics of the new models have more precision and clarity). The old website remains an excellent resource for fact-checking this migration. If you spot something that needs attention, please see [Contribute or get help](#contribute-or-get-help).

## Support and funding
This Species File functionality and content is serviced in part by the Species File Group.

## Terms of use (Copyright guidance)

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

