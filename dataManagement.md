---
lang: en
title: Data Management Plan
---

Copy of Amy\'s FOSS project 1
=============================

### Following the **Horizon 2020 DMP Template v2.0**

<div>

Contact person

:   -   [Clara Qin]{.contact-name}
        ([<claraqin@ucsc.edu>]{.contact-email}, [[]{.mini-orcid-icon-16}
        0000-0002-9561-4704]{.contact-orcid})\
        [University of California, Santa
        Cruz](https://ror.org/03s65by71)

Based on
:   Common DSW Knowledge Model, 2.3.0
    ([[dsw]{.organization-id}:[root]{.km-id}:[2.3.0]{.version}]{.package-id})

Created by
:   [Amy Schuler]{.contact-name}
    ([<schulera@caryinstitute.org>]{.contact-email})

Generated on
:   22 Mar 2021

Data Management Plan created in Data Stewardship Wizard
Â«[ds-wizard.org](https://ds-wizard.org)Â»

</div>

::: {#dmp-projects}
Projects
--------

We will be working on the following projects and for those are the data
and work described in this DMP.

::: {.project}
### Amy\'s test for Cary Institute

Acronym
:   Cary test

Start date
:   03/01/2021

End date
:   05/01/2021

Funding

:   -   [National Science
        Foundation](http://dx.doi.org/10.13039/100000001): n/a (planned)

::: {.section .abstract}
Basically this is a test drive of DSW for the Cary Institute. Right now
we have a \"home grown\" data management plan template that many
researchers use for (mainly) US federal grants. Most researchers create
their own based on that template, and perhaps a couple have used
DMPTool. I like the idea that DSWizard creates a machine readable data
management plan.
:::
:::

::: {.project}
### Clara Qin\'s undergraduate thesis turned manuscript

Acronym
:   Clara thesis

Start date
:   04/01/2014

End date
:   09/13/2019

Funding

:   -   Stanford Undergraduate Advising and Research (UAR) Major Grant:
        grant number not yet given (granted)
    -   A.W. Mellon Foundation / Stanford University Grant for Student
        Research at Jasper Ridge Biological Preserve: grant number not
        yet given (granted)

::: {.section .abstract}
Soil microbial communities regulate and respond to key biogeochemical
cycles and influence plant community patterns. However, microbial
communities also respond to disturbance events, motivating an assessment
of the relative roles of decadal multiâ€factor global change, disturbance
and plant community structure on microbial community responses.

We used highâ€throughput amplicon sequencing to characterize the
diversity and composition of bacterial and fungal communities in bulk
soil (0--7 cm) collected in 2014 from the Jasper Ridge Global Change
Experiment, a fullâ€factorial field experiment in which ambient and
elevated levels of nitrogen deposition (+7 g N mâˆ’2 yrâˆ’1 calcium
nitrate), CO2 concentration (+275 ppm), temperature (+1--2Â°C) and
precipitation (+50% volume with +3 weeks duration) were applied to a
California annual grassland from 1998 to 2014. We used linear
mixedâ€effects modelling to test for the effects of global change on
microbial diversity (observed richness, Shannon index). We also used
generalized dissimilarity modelling (GDM) to study controls on
compositional dissimilarity in fungal and bacterial communities.

Bacterial community composition was best explained by exposure to fires
in 2003 and 2011, whereas fungal community composition was best
explained by plant community composition. The richness of fungi
increased under elevated nitrogen deposition; bacterial diversity
metrics decreased under warmer temperatures. Interactions between global
change factors were statistically insignificant or weak.

Synthesis. Our results indicate that even on decadal timeâ€scales, the
effects of fire history and plant community composition on bacterial and
fungal community composition, respectively, outweigh the effects of
multiâ€factor global change. Furthermore, global change factors have
mostly additive effects on microbial diversity patterns. Our results
show that highly variable mediators such as fire history and plant
community composition limit the generalizability of soil microbial
responses to longâ€term global change.
:::
:::
:::

::: {#dmp-content}
::: {#sec-data-summary .section .dmp-section}
1. Data Summary
---------------

::: {#q-data-summary .question}
::: {.answer}
<div>

#### Non-equipment datasets

The non-equipment datasets are:

-   **Plant biomass** [--]{.separator} Plant biomass (g m-2 y-1) by
    species in each quadrant of each plot in the Jasper Ridge Global
    Change experiment in 2014.

</div>

<div>

#### Re-used datasets

<div>

We will use the following reference datasets:

-   **Cary Institute data repository. Supplementary File 5 - Fischhoff
    et al. 2021.**
    (<https://doi.org/10.25390/caryinstitute.13721254.v1>)

    We will use version \"v1\" of this dataset. If a new version becomes
    available during the project, new analyses will be done with the new
    version.

-   **Data from: Fire history and plant community composition outweigh
    decadal multiâ€factor global change as drivers of microbial
    composition in an annual grassland**
    (<https://doi.org/10.5061/dryad.nf481q8>)

</div>

</div>

#### Data formats and types

<div>

We will be using the following data formats and types:

-   **[Comma-separated Values](https://fairsharing.org/bsg-s001546)**

    It is a standardized format. This is a suitable format for long-term
    archiving. We will have only a small amount of data stored in this
    format.

-   **[DataCite Metadata Schema](https://fairsharing.org/bsg-s000588)**

    It is a standardized format. This is a suitable format for long-term
    archiving. We will have only a small amount of data stored in this
    format.

-   **[Biological Observation Matrix
    Ontology](https://fairsharing.org/bsg-s000884)**

    It is a standardized format. This is a suitable format for long-term
    archiving. We expect to have 0.0088 GB of data in this format.

-   **[Rich Text Format](https://fairsharing.org/bsg-s001263)**

    It is a standardized format. This is a suitable format for long-term
    archiving. We will have only a small amount of data stored in this
    format.

</div>
:::
:::
:::

::: {#sec-fair-data .section .dmp-section}
2. FAIR Data
------------

### 2.1. Making data findable, including provisions for metadata

::: {#q-findable .question}
::: {.answer}
-   **https://datadryad.org/stash/dataset/doi:10.5061/dryad.nf481q8**
    (published)\
    There won\'t be different versions of this data over time.\
    We will be adding a reference to the published data to at least one
    data catalogue.

There are no \'Minimal Metadata About \...\' (MIA\...) standards for our
experiments. However, we have a good idea of what metadata is needed to
make it possible for others to read and interpret your data in the
future.

We will use lab notebooks to make sure that there is good provenance of
the data analysis.
:::
:::

### 2.2. Making data openly accessible

::: {#q-accessible .question}
::: {.answer}
We will be working with the philosophy *as open as possible* for our
data.

All of our data can become completely open immediately.

All data will be owned by the Principal Investigator.

For the reference and non-reference data sets that we reuse, conditions
are as follows:

-   **Cary Institute data repository. Supplementary File 5 - Fischhoff
    et al. 2021.** [--]{.separator} freely available with obligation to
    quote the source (e.g. CC-BY).
-   **Data from: Fire history and plant community composition outweigh
    decadal multiâ€factor global change as drivers of microbial
    composition in an annual grassland** [--]{.separator} freely
    available with obligation to quote the source (e.g. CC-BY).

For our produced data, conditions are as follows:

-   **https://datadryad.org/stash/dataset/doi:10.5061/dryad.nf481q8**
    (published)\
    A user of this data can use it without any specific software.
:::
:::

### 2.3. Making data interoperable

::: {#q-interoperable .question}
<div>

We will be using the following data formats and types:

-   **[Comma-separated Values](https://fairsharing.org/bsg-s001546)**

    It is a standardized format.

-   **[DataCite Metadata Schema](https://fairsharing.org/bsg-s000588)**

    It is a standardized format.

-   **[Biological Observation Matrix
    Ontology](https://fairsharing.org/bsg-s000884)**

    It is a standardized format.

-   **[Rich Text Format](https://fairsharing.org/bsg-s001263)**

    It is a standardized format.

</div>

<div>

We will be using the following standards (encodings, terminologies,
vocabularies, ontologies):

-   **[Infectious Disease Ontology
    Core](https://fairsharing.org/bsg-s000095)**

</div>
:::

### 2.4. Increase data re-use (through clarifying licenses)

::: {#q-reusable .question}
::: {.answer}
The metadata for our produced data will be kept as follows:

-   **https://datadryad.org/stash/dataset/doi:10.5061/dryad.nf481q8**
    (published) [--]{.separator} This data set will be kept available as
    long as technically possible.

As stated already in Section 2.2, all of our data can become completely
open immediately.

We do not plan to be archiving data (using so-called *cold storage*) for
long term preservation already during your project.

To validate the integrity of the results, the following will be done:

-   We will run a subset of our jobs several times across the different
    compute infrastructures.
-   We will be instrumenting the tools into pipelines and workflows
    using automated tools.
-   We will use independently developed duplicate tools or workflows for
    critical steps to reduce or eliminate human errors.
-   We will run part of the data set repeatedly to catch unexpected
    changes in results.
:::
:::
:::

::: {#sec-resource-allocation .section .dmp-section}
3. Allocation of resources
--------------------------

::: {#q-resource-allocation .question}
::: {.answer}
FAIR is a central part of our data management; it is considered at every
decision in our data management plan. We use the FAIR data process
ourselves to make our use of the data as efficient as possible. Making
our data FAIR is therefore not a cost that can be separated from the
rest of the project.

None of the used repositories charge for their services.

We have a reserved budget for the time and effort it will take to
prepare the data for publication.

Amy Schuler is responsible for implementing the DMP, and ensuring it is
reviewed and revised.

Amy Schuler is responsible for reviewing, enhancing, cleaning, or
standardizing metadata and the associated data submitted for storage,
use and maintenance within a data centre or repository.

To execute the DMP, no additional specialist expertise is required.

We do not require any hardware or software in addition to what is
usually available in the institute.
:::
:::
:::

::: {#sec-data-security .section .dmp-section}
4. Data security
----------------

::: {#q-data-security .question}
::: {.answer}
Project members can carry data with them on password-protected laptops.
All data centers where project data is stored carry sufficient
certifications. All project web services addressed via secure http
(https://\...). Project members have been instructed about both generic
and specific risks to the project.

The possible impact to the project or organization if information is
lost is small. The possible impact to the project or organization if
information is leaked is small. The possible impact to the project or
organization if information is vandalised is small.

We are not using any personal information.
:::
:::
:::

::: {#sec-ethical-aspects .section .dmp-section}
5. Ethical aspects
------------------

::: {#q-ethical-aspects .question}
::: {.answer}
For the data we produce, the ethical aspects are as followsS:

-   **https://datadryad.org/stash/dataset/doi:10.5061/dryad.nf481q8**
    -   It does not contain personal data.
    -   It does not contain sensitive data.

We don\'t need any consent for collected data because those are not
personal.
:::
:::
:::

::: {#sec-other-issues .section .dmp-section}
6. Other issues
---------------

::: {#q-other-issues .question}
::: {.answer}
We use the [Data Stewardship Wizard](https://ds-wizard.org) with its
*Common DSW Knowledge Model* (ID:
[[dsw]{.organization-id}:[root]{.km-id}:[2.3.0]{.version}]{.package-id})
knowledge model to make our DMP. More specifically, we use the
<https://demo.ds-wizard.org> DSW instance where the project has direct
URL:
<https://demo.ds-wizard.org/projects/65bcd8d4-f7d0-4bbd-be2e-8cf4a2030c51>.
:::
:::
:::
:::
