# Life Sciences (life-sciences)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Industry-vertical index for the life sciences, biotechnology, and pharmaceutical landscape. Catalogs the major public and commercial APIs spanning clinical trial registries, drug and regulatory data, genomic reference data, electronic health record exchange, laboratory informatics systems, and bioinformatics pipeline platforms. The catalog is anchored by shared schemas for the three core records that recur across this domain: the clinical trial, the drug, and the gene.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/life-sciences/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/life-sciences/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Life Sciences
- Biotech
- Pharma
- Healthcare
- Clinical Trials
- Drug Information
- Genomics
- Bioinformatics
- EHR
- FHIR
- Lab Informatics

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-23

## APIs

### ClinicalTrials.gov API v2

The U.S. National Library of Medicine's modernized REST/JSON API for the ClinicalTrials.gov registry. Provides programmatic access to records of privately and publicly funded clinical studies conducted around the world, replacing the legacy AACT/full-study download path with a JSON-first interface and OpenAPI specification.

- **Human URL:** [https://clinicaltrials.gov/data-api/api](https://clinicaltrials.gov/data-api/api)
- **Base URL:** `https://clinicaltrials.gov/api/v2/`

#### Tags

- Clinical Trials
- Registry
- NIH
- NLM
- Public Data

#### Properties

- [Documentation](https://clinicaltrials.gov/data-api/api)
- [Documentation](https://clinicaltrials.gov/data-api/about-api)
- [OpenAPI](https://clinicaltrials.gov/api/v2/swagger.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/life-sciences/refs/heads/main/json-schema/clinical-trial-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](https://raw.githubusercontent.com/api-evangelist/life-sciences/refs/heads/main/examples/clinical-trial-example.json)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EU Clinical Trials Register / CTIS

The European Medicines Agency's Clinical Trials Information System (CTIS) and the legacy EU Clinical Trials Register. CTIS is the single entry point for sponsors and regulators across the EU/EEA to submit and supervise clinical trials under Regulation (EU) No 536/2014. Public lookup is offered through a web portal; bulk and integration interfaces are not openly published as REST APIs.

- **Human URL:** [https://euclinicaltrials.eu/](https://euclinicaltrials.eu/)
- **Base URL:** `https://euclinicaltrials.eu/ctis-public/`

#### Tags

- Clinical Trials
- EU
- EMA
- Regulator
- CTIS

#### Properties

- [Documentation](https://euclinicaltrials.eu/)
- [Documentation](https://www.ema.europa.eu/en/human-regulatory-overview/research-development/clinical-trials-human-medicines/clinical-trials-information-system)
- [Human Interface](https://www.clinicaltrialsregister.eu/)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### openFDA

A U.S. Food and Drug Administration project that exposes public FDA data via a single Elasticsearch-backed REST/JSON API. Covers adverse-event reports, drug labels, recalls, NDC directory, device 510(k) and adverse events, food enforcement, tobacco problem reports, and animal/vet adverse events.

- **Human URL:** [https://open.fda.gov/](https://open.fda.gov/)
- **Base URL:** `https://api.fda.gov/`

#### Tags

- FDA
- Drug
- Device
- Food
- Adverse Events
- Regulator

#### Properties

- [Documentation](https://open.fda.gov/apis/)
- [Documentation](https://open.fda.gov/apis/drug/)
- [Documentation](https://open.fda.gov/apis/device/)
- [Documentation](https://open.fda.gov/apis/food/)
- [GitHub Repository](https://github.com/FDA/openfda)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/life-sciences/refs/heads/main/json-schema/drug-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](https://raw.githubusercontent.com/api-evangelist/life-sciences/refs/heads/main/examples/drug-example.json)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DailyMed

The National Library of Medicine's authoritative source of FDA-approved Structured Product Labeling (SPL) for prescription and over-the-counter medications marketed in the United States. Exposes a REST/JSON web services API for searching and retrieving SPL documents by SET ID, NDC, RxCUI, and other identifiers.

- **Human URL:** [https://dailymed.nlm.nih.gov/dailymed/](https://dailymed.nlm.nih.gov/dailymed/)
- **Base URL:** `https://dailymed.nlm.nih.gov/dailymed/services/v2/`

#### Tags

- Drug Information
- Labeling
- SPL
- NLM

#### Properties

- [Documentation](https://dailymed.nlm.nih.gov/dailymed/app-support-web-services.cfm)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### RxNorm API

The National Library of Medicine's web service for accessing RxNorm, the standardized nomenclature for clinical drugs that links names of drugs across the major U.S. drug vocabularies. Supports name-to-RxCUI resolution, NDC lookup, relationship traversal, interaction discovery via RxNav, and approximate matching.

- **Human URL:** [https://lhncbc.nlm.nih.gov/RxNav/APIs/RxNormAPIs.html](https://lhncbc.nlm.nih.gov/RxNav/APIs/RxNormAPIs.html)
- **Base URL:** `https://rxnav.nlm.nih.gov/REST/`

#### Tags

- Drug Information
- Terminology
- NLM
- RxNorm

#### Properties

- [Documentation](https://lhncbc.nlm.nih.gov/RxNav/APIs/RxNormAPIs.html)
- [Documentation](https://lhncbc.nlm.nih.gov/RxNav/APIs/InteractionAPIs.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/life-sciences/refs/heads/main/json-schema/drug-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DrugBank API

A commercial drug knowledge API providing curated pharmacology, pharmacokinetics, drug-drug interaction, indication, and identifier cross-walk data covering small molecules and biologics. Used by clinical decision support, electronic prescribing, and pharmacy systems.

- **Human URL:** [https://docs.drugbank.com/v1/](https://docs.drugbank.com/v1/)
- **Base URL:** `https://api.drugbankplus.com/v1/`

#### Tags

- Drug Information
- Pharmacology
- Interactions
- Commercial

#### Properties

- [Documentation](https://docs.drugbank.com/v1/)
- [Documentation](https://go.drugbank.com/)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NCBI Entrez E-utilities

The set of nine programmatic interfaces (ESearch, EPost, ESummary, EFetch, ELink, EInfo, EGQuery, ESpell, ECitMatch) that provide unified access to all NCBI databases including PubMed, Gene, Genome, Nucleotide, Protein, ClinVar, dbSNP, dbGaP, BioProject, BioSample, GEO, and Taxonomy.

- **Human URL:** [https://www.ncbi.nlm.nih.gov/books/NBK25500/](https://www.ncbi.nlm.nih.gov/books/NBK25500/)
- **Base URL:** `https://eutils.ncbi.nlm.nih.gov/entrez/eutils/`

#### Tags

- Genomics
- Bioinformatics
- NCBI
- PubMed
- Reference Data

#### Properties

- [Documentation](https://www.ncbi.nlm.nih.gov/books/NBK25500/)
- [Documentation](https://www.ncbi.nlm.nih.gov/books/NBK25501/)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/life-sciences/refs/heads/main/json-schema/gene-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ensembl REST API

The European Bioinformatics Institute's REST/JSON interface to the Ensembl genome browser. Provides programmatic access to genomic annotation, variation, comparative genomics, regulatory data, the Variant Effect Predictor (VEP), and GA4GH-compatible variation endpoints across vertebrate, invertebrate, plant, and fungal genomes.

- **Human URL:** [https://rest.ensembl.org/](https://rest.ensembl.org/)
- **Base URL:** `https://rest.ensembl.org/`

#### Tags

- Genomics
- Variation
- VEP
- EBI
- GA4GH

#### Properties

- [Documentation](https://rest.ensembl.org/)
- [Documentation](https://rest.ensembl.org/documentation/info/vep_hgvs_get)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/life-sciences/refs/heads/main/json-schema/gene-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](https://raw.githubusercontent.com/api-evangelist/life-sciences/refs/heads/main/examples/gene-example.json)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### UCSC Genome Browser REST API

The University of California Santa Cruz Genome Browser's REST API for programmatic retrieval of assemblies, tracks, sequences, and annotations across the genomes hosted in the UCSC Browser, including human (hg19, hg38, T2T-CHM13), mouse, and many other species.

- **Human URL:** [https://genome.ucsc.edu/goldenPath/help/api.html](https://genome.ucsc.edu/goldenPath/help/api.html)
- **Base URL:** `https://api.genome.ucsc.edu/`

#### Tags

- Genomics
- Reference Genome
- UCSC
- Tracks

#### Properties

- [Documentation](https://genome.ucsc.edu/goldenPath/help/api.html)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ClinVar (via E-utilities)

The NIH/NLM database of relationships among human genomic variation and phenotype, with supporting evidence. Accessible programmatically via Entrez E-utilities and via a structured FTP feed of XML/JSON variant submissions.

- **Human URL:** [https://www.ncbi.nlm.nih.gov/clinvar/](https://www.ncbi.nlm.nih.gov/clinvar/)
- **Base URL:** `https://eutils.ncbi.nlm.nih.gov/entrez/eutils/`

#### Tags

- Variation
- Clinical Genomics
- NCBI
- ClinVar

#### Properties

- [Documentation](https://www.ncbi.nlm.nih.gov/clinvar/docs/maintenance_use/)
- [Documentation](https://www.ncbi.nlm.nih.gov/clinvar/docs/linking/)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### dbSNP (via E-utilities)

The NCBI Short Genetic Variations database, the canonical reference for single nucleotide polymorphisms (SNPs) and small insertions/deletions in humans and other organisms. Accessed via Entrez E-utilities using the `snp` database.

- **Human URL:** [https://www.ncbi.nlm.nih.gov/snp/](https://www.ncbi.nlm.nih.gov/snp/)
- **Base URL:** `https://eutils.ncbi.nlm.nih.gov/entrez/eutils/`

#### Tags

- Variation
- SNP
- NCBI
- dbSNP

#### Properties

- [Documentation](https://www.ncbi.nlm.nih.gov/snp/docs/)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### HL7 FHIR

Fast Healthcare Interoperability Resources (FHIR) is HL7's standard for health care data exchange. The current normative version is R5, released March 2023. Defines roughly 150 resource types covering administration, clinical care, diagnostics, medications, workflow, financial, and foundation domains, exchanged over REST, messaging, or document paradigms.

- **Human URL:** [https://www.hl7.org/fhir/](https://www.hl7.org/fhir/)
- **Base URL:** `https://hl7.org/fhir/R5/`

#### Tags

- FHIR
- HL7
- EHR
- Healthcare Interoperability
- Standard

#### Properties

- [Documentation](https://www.hl7.org/fhir/)
- [Specification](https://hl7.org/fhir/R5/)
- [JSON Schema](https://hl7.org/fhir/R5/fhir.schema.json.zip) — [JSON Schema](https://json-schema.org/specification)
- [GitHub Repository](https://github.com/HL7/fhir)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SMART on FHIR

An open-spec authorization profile layered on top of FHIR that enables third-party clinical applications to launch within an EHR session with OAuth 2.0 / OpenID Connect scopes scoped to FHIR resources.

- **Human URL:** [https://docs.smarthealthit.org/](https://docs.smarthealthit.org/)
- **Base URL:** `https://docs.smarthealthit.org/`

#### Tags

- FHIR
- SMART
- OAuth
- EHR
- Standard

#### Properties

- [Documentation](https://docs.smarthealthit.org/)
- [GitHub Repository](https://github.com/smart-on-fhir)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Benchling Developer Platform

Benchling's REST API and webhook platform for its R&D cloud, exposing programmatic access to the Notebook (entries), Registry (registered entities, sequences, plasmids), Inventory (boxes, plates, locations), Requests, Results, Schemas, and Projects domains used across biotech R&D organizations.

- **Human URL:** [https://docs.benchling.com/](https://docs.benchling.com/)
- **Base URL:** `https://{tenant}.benchling.com/api/v2/`

#### Tags

- Lab Informatics
- ELN
- LIMS
- Biotech
- Commercial

#### Properties

- [Documentation](https://docs.benchling.com/)
- [Documentation](https://docs.benchling.com/reference)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TetraScience Data Platform

A cloud-native scientific data platform that harmonizes instrument and informatics data across pharma R&D. Exposes REST APIs and SDKs for ingesting, querying, and integrating laboratory and computational data using the Intermediate Data Schema (IDS).

- **Human URL:** [https://developers.tetrascience.com/](https://developers.tetrascience.com/)
- **Base URL:** `https://developers.tetrascience.com/`

#### Tags

- Lab Informatics
- Scientific Data
- IDS
- Commercial

#### Properties

- [Documentation](https://developers.tetrascience.com/)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sapio Sciences ELN/LIMS API

Sapio Sciences' platform API providing programmatic access to its Electronic Laboratory Notebook, Laboratory Information Management System, and Scientific Data Cloud, covering samples, experiments, assay results, and inventory.

- **Human URL:** [https://www.sapiosciences.com/](https://www.sapiosciences.com/)
- **Base URL:** `https://www.sapiosciences.com/`

#### Tags

- Lab Informatics
- ELN
- LIMS
- Commercial

#### Properties

- [Documentation](https://www.sapiosciences.com/)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DNAnexus Platform API

DNAnexus is a cloud bioinformatics platform used by pharma, biotech, and research institutions to run genomic and biomedical compute workflows. Its platform API provides programmatic access to projects, files, apps, workflows, jobs, and analyses for petabyte-scale genomic data.

- **Human URL:** [https://documentation.dnanexus.com/](https://documentation.dnanexus.com/)
- **Base URL:** `https://api.dnanexus.com/`

#### Tags

- Bioinformatics
- Cloud Compute
- Workflows
- Commercial

#### Properties

- [Documentation](https://documentation.dnanexus.com/)
- [Documentation](https://documentation.dnanexus.com/developer/api)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Seven Bridges (Velsera) Platform API

A multi-cloud bioinformatics platform (now part of Velsera) offering hosted instances of the NCI Cancer Genomics Cloud and other cohort analysis environments. Provides REST APIs for projects, files, tasks, and apps written in CWL.

- **Human URL:** [https://docs.sevenbridges.com/](https://docs.sevenbridges.com/)
- **Base URL:** `https://api.sbgenomics.com/v2/`

#### Tags

- Bioinformatics
- Cloud Compute
- CWL
- Cancer Genomics

#### Properties

- [Documentation](https://docs.sevenbridges.com/)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Galaxy Project API

The open-source Galaxy bioinformatics workbench exposes a REST API for managing histories, datasets, workflows, tools, jobs, and users across community Galaxy servers and self-hosted installations.

- **Human URL:** [https://docs.galaxyproject.org/en/latest/api_doc.html](https://docs.galaxyproject.org/en/latest/api_doc.html)
- **Base URL:** `https://usegalaxy.org/api/`

#### Tags

- Bioinformatics
- Open Source
- Workflows
- Galaxy

#### Properties

- [Documentation](https://docs.galaxyproject.org/en/latest/api_doc.html)
- [GitHub Repository](https://github.com/galaxyproject/galaxy)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GA4GH APIs (htsget, DRS, WES, TES, Beacon)

The Global Alliance for Genomics and Health publishes a suite of open REST specifications enabling federated access to genomic data and compute. Includes htsget (sequencing reads), DRS (Data Repository Service), WES (Workflow Execution Service), TES (Task Execution Service), and the Beacon variant-discovery protocol.

- **Human URL:** [https://www.ga4gh.org/genomic-data-toolkit/](https://www.ga4gh.org/genomic-data-toolkit/)
- **Base URL:** `https://www.ga4gh.org/`

#### Tags

- Genomics
- Standard
- GA4GH
- Federated

#### Properties

- [Documentation](https://www.ga4gh.org/genomic-data-toolkit/)
- [GitHub Repository](https://github.com/ga4gh)
- [Specification](https://samtools.github.io/hts-specs/htsget.html)
- [Specification](https://ga4gh.github.io/beacon/)
- [Postman Collection](collections/life-sciences.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/life-sciences.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
