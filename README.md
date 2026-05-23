# Life Sciences (life-sciences)

Industry-vertical index for the life sciences, biotechnology, and pharmaceutical landscape. Catalogs the major public and commercial APIs spanning clinical trial registries, drug and regulatory data, genomic reference data, electronic health record exchange, laboratory informatics systems, and bioinformatics pipeline platforms. The catalog is anchored by shared schemas for the three core records that recur across this domain: the clinical trial, the drug, and the gene.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/life-sciences/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

Life Sciences, Biotech, Pharma, Healthcare, Clinical Trials, Drug Information, Genomics, Bioinformatics, EHR, FHIR, Lab Informatics

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-23

## APIs

### ClinicalTrials.gov API v2
The U.S. National Library of Medicine's modernized REST/JSON API for the ClinicalTrials.gov registry. Provides programmatic access to records of privately and publicly funded clinical studies conducted around the world.
- [Documentation](https://clinicaltrials.gov/data-api/api)
- [OpenAPI](https://clinicaltrials.gov/api/v2/swagger.yaml)
- [Clinical Trial Schema](json-schema/clinical-trial-schema.json)
- [Clinical Trial Example](examples/clinical-trial-example.json)

### EU Clinical Trials Register / CTIS
The European Medicines Agency's Clinical Trials Information System and the legacy EU Clinical Trials Register.
- [CTIS Public Portal](https://euclinicaltrials.eu/)
- [EMA CTIS overview](https://www.ema.europa.eu/en/human-regulatory-overview/research-development/clinical-trials-human-medicines/clinical-trials-information-system)

### openFDA
A U.S. Food and Drug Administration project exposing public FDA data via a single Elasticsearch-backed REST/JSON API across drug, device, and food domains.
- [Documentation](https://open.fda.gov/apis/)
- [GitHub](https://github.com/FDA/openfda)
- [Drug Schema](json-schema/drug-schema.json)

### DailyMed
NLM's authoritative source of FDA-approved Structured Product Labeling (SPL).
- [Web Services](https://dailymed.nlm.nih.gov/dailymed/app-support-web-services.cfm)

### RxNorm API
NLM's web service for the standardized clinical drug nomenclature linking names across major U.S. drug vocabularies.
- [Documentation](https://lhncbc.nlm.nih.gov/RxNav/APIs/RxNormAPIs.html)
- [Interaction API](https://lhncbc.nlm.nih.gov/RxNav/APIs/InteractionAPIs.html)

### DrugBank API
Commercial drug knowledge API providing curated pharmacology, pharmacokinetics, interactions, indications, and identifier crosswalks.
- [Documentation](https://docs.drugbank.com/v1/)

### NCBI Entrez E-utilities
Nine programmatic interfaces (ESearch, EPost, ESummary, EFetch, ELink, EInfo, EGQuery, ESpell, ECitMatch) providing unified access to all NCBI databases.
- [Documentation](https://www.ncbi.nlm.nih.gov/books/NBK25500/)
- [Gene Schema](json-schema/gene-schema.json)

### Ensembl REST API
EBI's REST/JSON interface to the Ensembl genome browser — annotation, variation, comparative genomics, regulatory data, and VEP.
- [Documentation](https://rest.ensembl.org/)
- [Gene Example](examples/gene-example.json)

### UCSC Genome Browser REST API
REST API for assemblies, tracks, sequences, and annotations across UCSC-hosted genomes.
- [Documentation](https://genome.ucsc.edu/goldenPath/help/api.html)

### ClinVar (via E-utilities)
NIH database of relationships among human variation and phenotype.
- [Documentation](https://www.ncbi.nlm.nih.gov/clinvar/docs/maintenance_use/)

### dbSNP (via E-utilities)
Canonical reference for SNPs and small indels in humans and other organisms.
- [Documentation](https://www.ncbi.nlm.nih.gov/snp/docs/)

### HL7 FHIR
HL7's standard for health care data exchange (current normative version R5, March 2023).
- [Documentation](https://www.hl7.org/fhir/)
- [Specification (R5)](https://hl7.org/fhir/R5/)
- [GitHub](https://github.com/HL7/fhir)

### SMART on FHIR
Authorization profile layered on FHIR enabling third-party clinical apps to launch inside an EHR session.
- [Documentation](https://docs.smarthealthit.org/)
- [GitHub](https://github.com/smart-on-fhir)

### Benchling Developer Platform
Benchling's REST API and webhook platform for its R&D cloud — Notebook, Registry, Inventory, Requests, Results, Schemas, Projects.
- [Documentation](https://docs.benchling.com/)

### TetraScience Data Platform
Cloud-native scientific data platform harmonizing instrument and informatics data across pharma R&D.
- [Documentation](https://developers.tetrascience.com/)

### Sapio Sciences ELN/LIMS API
Sapio's ELN, LIMS, and Scientific Data Cloud platform API.
- [Documentation](https://www.sapiosciences.com/)

### DNAnexus Platform API
Cloud bioinformatics platform for genomic and biomedical compute at petabyte scale.
- [Documentation](https://documentation.dnanexus.com/)

### Seven Bridges (Velsera) Platform API
Multi-cloud bioinformatics platform hosting the NCI Cancer Genomics Cloud and other cohort analysis environments.
- [Documentation](https://docs.sevenbridges.com/)

### Galaxy Project API
Open-source Galaxy bioinformatics workbench REST API.
- [Documentation](https://docs.galaxyproject.org/en/latest/api_doc.html)
- [GitHub](https://github.com/galaxyproject/galaxy)

### GA4GH APIs (htsget, DRS, WES, TES, Beacon)
Global Alliance for Genomics and Health open REST specifications for federated genomic data and compute.
- [Genomic Data Toolkit](https://www.ga4gh.org/genomic-data-toolkit/)
- [GitHub](https://github.com/ga4gh)
- [htsget specification](https://samtools.github.io/hts-specs/htsget.html)
- [Beacon specification](https://ga4gh.github.io/beacon/)

## Artifacts

### JSON Schema
- [Clinical Trial Schema](json-schema/clinical-trial-schema.json)
- [Drug Schema](json-schema/drug-schema.json)
- [Gene Schema](json-schema/gene-schema.json)

### Examples
- [Clinical Trial Example](examples/clinical-trial-example.json)
- [Drug Example](examples/drug-example.json)
- [Gene Example](examples/gene-example.json)

### JSON-LD
- [Life Sciences Context](json-ld/life-sciences-context.jsonld)

### Vocabulary
- [Life Sciences Vocabulary](vocabulary/life-sciences-vocabulary.yaml)
