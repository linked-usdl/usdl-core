Linked USDL - Core Module
=========
Linked USDL (http://www.linked-usdl.org) is the latest evolution of the Unified Service Description Language (http://www.internet-of-services.com/index.php?id=288&L=0), the most comprehensive approach to supporting the description of real-world services for their automated processing and trading online. The language supports the creation of structured descriptions of services covering most relevant characteristics ranging from technical aspects, to operational ones, socio-economic concerns, or even legal issues. 

Linked USDL builds upon the results and experience gained with USDL combined with prior research on Semantic Web Services, business ontologies, and Linked Data to better support Web-scale automated service trading. Linked USDL adopts and exploits Linked Data to be scalable for the Web, to promote and simplify its adoption by reusing vocabularies and datasets, and to benefit from a high level of genericity and adaptability for domain specific modelling.

Linked USDL Core is the foundation module of Linked USDL and covers four essential aspects: 
- Service descriptions
- Service offering descriptions
- Business entities involved in the service delivery chain
- Interaction points allowing consumers to contract or trigger the benefits of contracted services

Linked USDL Core relies on a number of pre-existing vocabularies, namely:
– DC Terms to cover general purpose metadata such as the creator of a certain description, its date of creation or modification, etc.
– SKOS for low-cost support for capturing knowledge organisation systems (e.g., classifications and thesauri) in RDF.
- Time Ontology for covering basic temporal relations between instants and intervals. Time Ontology essentially allows us for instance to capture temporal relationships such as before and during.
- vCard vocabulary a vCard 4 compatible vocabulary to support providing location and contact information for people and organisations.
- Minimal Service Model (MSM) to provide coverage for automated service-based interactions including Remote Procedure Call solutions (e.g., WSDL services) and RESTful services.
- GR to provide core coverage for services, business entities, offerings, and their relationship with products.

Finally, and in the interest of providing self-contained support for most basic features, we include a number of SKOS categorisations that users can directly integrate in their applications covering Business Roles, Interation Roles and Interaction Types.

Linked USDL Core is expected to be supplemented by additional vocabularies for describing princing models, agreements, legal aspects, etc. Check out the rest of the projects in GitHub (https://github.com/linked-usdl) for these and related open source tools that could help you benefit from Linked USDL. 
