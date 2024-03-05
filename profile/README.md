# Open Semantic Lab

Open Semantic Lab (OSL) is a holistic web platform that can capture all data and ideas and link them precisely (semantically/ontology-based) - no matter if it' s inventory (LIMS), lab notes (ELN), procedures (SOPs) or research (KB). 
Each piece of information can also be machine-read, blockchain-signed and written to automatically transfer (Lab 4.0) and analyze (AI) measurement data. 
OSL actively supports between the unstructured (liquid) and highly structured / ontologized phase of knowledge within organizations the formation of a partially structured (amorphous) phase, which acts as a (crystallization) seed for the consistent growth of the highly structured phase.
As an open system, Open Semantic Lab can be easily adapted with little to none programming knowledge without losing the uniform structure. 
In this way, we can contribute to everyone's knowledge individually and yet in a standardized way.

General Introduction 
* [Documentation](https://opensemantic.world/wiki/Item:OSWdb485a954a88465287b341d2897a84d6)
* Talk at [SMWCon2022](https://youtu.be/aBl6i7k4pIY)
* [OpenSemanticLab.pdf](https://github.com/OpenSemanticLab/.github/files/9684923/2022-08-31_OpenSemanticLab.pdf)
* [Podcast Episode @ Between the Brackets](https://betweenthebrackets.libsyn.com/episode-129-simon-stier)

Short Introduction @ [EMIRI Workshop](https://emiri.eu/2022/07/04/digital-revolution-in-materials-discovery/) "RE-INVENTING MATERIALS RESEARCH" as [PDF](https://emiri.eu/wp-content/uploads/2022/07/7.-2022-06-30_MAP-Workshop_Grenoble_OpenSemanticLab_v2.pdf) or [Video](https://youtu.be/MZlk5Gzy0tc?t=1564)

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
* Node-RED as Dashboard-Solution
* A [Python Toolset](https://github.com/OpenSemanticLab/osw-python)
* Connectors to platforms like [IDS](https://internationaldataspaces.org/), [PMD](https://material-digital.de/), [NFDI/FAIRmat/NOMAD/OASIS](https://www.fairmat-nfdi.eu) etc. (tbd)
* Interfaces to other ELN / LIMS tools like [openBIS](https://openbis.ch/) (in work)

## Current state
* Prototype-Level, applied in multiple research project, e. g. [KIproBatt](https://kiprobatt.de/wiki), [Onterface](https://onterface.open-semantic-lab.org/wiki/) and [OntoWiki](https://onto-wiki.eu/wiki/Main_Page)
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




## Contact
* https://www.isc.fraunhofer.de/digitale-transformation
