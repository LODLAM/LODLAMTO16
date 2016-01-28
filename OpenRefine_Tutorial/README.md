#Going from Theory to Practice:
###Preparing + Leveraging Linked Open Metadata with OpenRefine
**Day 1, 1:30–4:30**
[Christina Harlow (Cornell University)](http://www.twitter.com/cm_harlow)
cmh329@cornell.edu

##Abstract
This interactive tutorial will walk you through taking existing metadata, enhancing it, then producing it as RDF. We will use OpenRefine, an open source tool for working with data, and the DERI RDF Extension for OpenRefine, to walk through this work. A little bit of time will be given to the data normalization features of OpenRefine - faceting, Clustering, GREL (Google Refine Expression Language). However, the real focus will be on how to leverage existing and produce your own RDF data. Reconciliation of entities with external SPARQL Endpoints and RDF datasets, along with RDF mapping and production, will be covered in depth. Participants are strongly encouraged to install OpenRefine and follow along.

**Note to Participants**: Please have OpenRefine and the DERI RDF Extension or LODRefine installed before the start of the workshop if you wish to participate in hands on work. Instructions for installation are available at [Installation](Installation/README.md). If you run into any issues with installation, please get in touch with [me](mailto:cmh329@cornell.edu) as soon as you are able, and I'll work through these issues with you.

##Agenda
1. Introduction to OpenRefine: Both Utilizing & Producing RDF
    2. About
    3. Extensions
    4. LODRefine
    6. Resources
2. Import Data
    3. CSV, Google Sheets
    4. JSON, XML
    5. RDF/XML, RDF Ntriples
3. Data Remediation/Munging (Briefly)
    4. Faceting, Clustering
    5. GREL
4. Reconciliation
    5. Add a column/hit APIs
    6. Standard Reconciliation Services
    7. SPARQL Reconciliation
    8. RDF Reconciliation
    10. Capturing URIs
5. Mapping to RDF
    6. Creating an RDF skeleton
    7. Adding Namespaces
    8. Working with rdf:type, blank nodes
    9. Outputing RDF/XML, RDF Turtle
6. Questions + Comments

##Tutorial Project
Follow along with the tutorial project. By the end, we won't have *perfect* or *complete* RDF metadata, but we'll know how to get there (or how to improve our metadata regardless).

- Import sample DC/XML metadata (pulled from real life Fedora 3 to 4 migration) to make into RDF
    - Heartache of importing XML
    - Cleaning, Normalizing terms
    - Mapping to columns that will become predicates
    - Pulling in URIs for certain fields through Reconciliation API
    - Mapping our tabular data to RDF
    - Exporting RDF
- You're also welcome to bring your own data & follow along working on that

##Contents of this Directory
- Slides
- Installation Instructions
- Procedures Documentation
- Sample Data, Projects

##Community Notes

Feel free to add notes from the session here, if so moved (just submit a pull request and I'll merge).
