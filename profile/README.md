[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.11355585.svg )](https://doi.org/10.5281/zenodo.11355585  )
# Open Semantic Lab

Open Semantic Lab (OSL) is a holistic web platform that can capture all data and ideas and link them precisely (semantically/ontology-based) - no matter if it' s inventory (LIMS), lab notes (ELN), procedures (SOPs) or research (KB). 
Each piece of information can also be machine-read, blockchain-signed and written to automatically transfer (Lab 4.0) and analyze (AI) measurement data. 
OSL actively supports between the unstructured (liquid) and highly structured / ontologized phase of knowledge within organizations the formation of a partially structured (amorphous) phase, which acts as a (crystallization) seed for the consistent growth of the highly structured phase.
As an open system, Open Semantic Lab can be easily adapted with little to none programming knowledge without losing the uniform structure. 
In this way, we can contribute to everyone's knowledge individually and yet in a standardized way.

General Introduction 
* Talk at [SMWCon2022](https://youtu.be/aBl6i7k4pIY), [SMWCon2023](https://www.youtube.com/watch?v=wHA0DO-zW5A) and [SMWCon2024](https://www.youtube.com/watch?v=oHih-bV5E_0)
* [OpenSemanticLab.pdf](https://github.com/OpenSemanticLab/.github/files/9684923/2022-08-31_OpenSemanticLab.pdf)
* [Documentation](https://demo.open-semantic-lab.org/wiki/Item:OSW8bccb1f0123f47d1831a1348ecbe63cc)
* [Podcast Episode @ Between the Brackets](https://betweenthebrackets.libsyn.com/episode-129-simon-stier)

Related common compontents: [OpenSemanticWorld](https://github.com/OpenSemanticWorld)
and content packages: [OpenSemanticWorld-Packages](https://github.com/OpenSemanticWorld-Packages), hosted on [opensemantic.world](https://opensemantic.world)

## Which problems are addressed?

### Loss of knowledge
Most of the knowledge generated in industry and science is irrevocably lost because we lack suitable tools for sustainable and complete documentation.

### AI accessible data structure
In addition, generated data can only be structured and made accessible to AI with a great deal of additional effort. 

## What are the core components?
* An object oriented linked data schema, see [OO-LD](https://github.com/OO-LD/schema)
* MediaWiki, extented with Semantic MediaWiki and various other existing extensions
* The Mediawiki extension ['OpenSemanticLab'](https://github.com/OpenSemanticLab/mediawiki-extensions-OpenSemanticLab)
* Ontologies, especially the [General Process Ontology](https://github.com/General-Process-Ontology/ontology)
* A Graph-Database, currently blazegraph
* A Time-Series-Database, currently TimeScaleDB
* JupyterHub as Workflow-Environment
* [Panel](https://github.com/holoviz/panel) as Dashboard-Solution
* A [Python Toolset](https://github.com/OpenSemanticLab/osw-python)
* An [agentic AI chatbot framework](https://github.com/opensemanticworld/osw-chatbot)

## Current state
* Prototype-Level, applied in multiple research project, e. g. [KIproBatt](https://kiprobatt.de/wiki), [Battery Knowledge Graph](https://battery.knowledge-graph.eu/), [BIG-MAP Onterface](https://onterface.open-semantic-lab.org/wiki/)
* Docker [container](https://github.com/OpenSemanticLab/docker-compose-osl-wiki) & [compose](https://github.com/OpenSemanticLab/osl-mw-docker-compose) 
* [Demo-Instance](https://demo.open-semantic-lab.org) (work in progress)
* [Central Schema Repo/Registry](https://opensemantic.world)

## Screenshots
### OpenSemanticLab custom landing page displaying the available apps (described by installed schemas)
![grafik](https://github.com/OpenSemanticLab/.github/assets/52674635/3284cf2c-fdf7-442d-ba64-596a101d6817)
### OpenSemanticLab workflow to build user specific apps
![grafik](https://github.com/OpenSemanticLab/.github/assets/52674635/4aa7344e-95d3-4491-ad72-6cffcc93bace)
### Example of a knowledge graph of various experiments created with OpenSemanticLab
![grafik](https://github.com/OpenSemanticLab/.github/assets/52674635/455dadb0-82d2-4563-abac-a3e2d87d5185)

## Demos
### KIproBatt Battery Production Knowledge Graph
![grafik](https://raw.githubusercontent.com/KIproBatt/kiprobatt-dataset/main/docs/KIproBatt-KnowledgeGraph-WalkThrough.min.gif)

[video link](https://raw.githubusercontent.com/KIproBatt/kiprobatt-dataset/main/docs/KIproBatt-KnowledgeGraph-WalkThrough.mp4)

### Chatbot Interface

https://github.com/user-attachments/assets/8760397a-3089-4758-b480-d2cee9463234
> AI assisted form-completion based on a uploaded data sheet


[![LLM Agentic with Code Generation for Scientific Data Analysis](http://img.youtube.com/vi/8XypKdFaxpM/0.jpg)](http://www.youtube.com/watch?v=8XypKdFaxpM "LLM Agentic with Code Generation for Scientific Data Analysis")
> LLM Agentic with Code Generation for Scientific Data Analysis

## Related projects and initiatives
OpenSemanticLab was adapted/showcased in the following projects and initiatives. Funding information see individual pages / repositories.
| Name      | Scope | Activity | Link |
| ----------- | ----------- | ----------- | ----------- |
| KIproBatt      | National (BMBF)       | Adapted | https://kiprobatt.de |
| Mat-o-Lab      | National (BMBF)       | Adapted| https://mat-o-lab.open-semantic-lab.org/ |
| MaterialDigital      | National (BMBF)       | Showcased | https://material-digital.de/  / [Ontology Playground](https://forum.materialdigital.de/t/onboarding-semantische-interoperabilitaet/257) |
| NFDI MatWerk | National (DFG) | Showcased | https://nfdi-matwerk.de/nfdi/2023/ |
| BIG-MAP   | EU (HE)        | Adapted | https://big-map.eu/ / [Onterface](https://onterface.open-semantic-lab.org) |
| Battery2030+   | EU (HE)        | Adapted | https://battery.knowledge-graph.eu |
| CircEl-Paper   | EU (HE)        | Adapted  | https://circelpaper.projects01.open-semantic-lab.org |
| ReUse   | EU (HE)        | Adapted | https://reuse.projects01.open-semantic-lab.org/ |

## Contact
* https://www.isc.fraunhofer.de/digitale-transformation
