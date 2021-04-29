# LA-CoNGA Physics Metadata

The contents created in the LA-CoNGA Physics activities will be defined in an open science framework, open access to these will be essential and actions will be developed so that they comply with the [FAIR principles](https://www.go-fair.org/fair-principles/). The **Dublin Core** metadata schema will be used to describe the content created and facilitate its discovery.

## Dublin Core scheme

Dublin Core metadata is designed for interoperability. Metadata in this style uses Uniform Resource Identifiers (URIs) as global identifiers both for the things described by the metadata and for the terms used to describe them (vocabularies). The use of specialized metadata vocabularies such as Dublin Core enables resource discovery.

### Dublin Core Vocabulary

In a first stage, the contents defined as LA-CoNGA Physics products and framed in the **Dublin Core** vocabulary are:

- **Collection** - "An aggregation of resources"  
A collection is described as a group; its parts may also be separately described. Examples: Word Documents or MkDocs Projects
- **Dataset** - "Data encoded in a defined structure"
Examples include lists, tables, and databases. A dataset may be useful for direct machine processing.
- **Event** - "A non-persistent, time-based occurrence"   
Comment Metadata for an event provides descriptive information that is the basis for discovery of the purpose, location, duration, and responsible agents associated with an event. Examples include seminars or hackatons
- **Image** - "A visual representation other than text"   
Examples include images and photographs of physical objects, plots, prints, drawings, other images and graphics, animations and moving pictures, film, diagrams, maps. Note that Image may include both electronic and physical representations.
- **InteractiveResource** - "A resource requiring interaction from the user to be understood, executed, or experienced"  
Examples include forms on Web pages or chat services like mattermost.
- **MovingImage** - "A series of visual representations imparting an impression of motion when shown in succession"   
Examples include animations, class recording, video tutorials or video description of experiments. Instances of the type Moving Image must also be describable as instances of the broader type Image.
- **Software** - "A computer program in source or compiled form"  
Examples include a Jupyter Notebook, a C++ script, a python script or more elaborate software like ROOT Framework.
- **Sound** - "A resource primarily intended to be heard"   
Examples include a music playback file format, or audio recordings of classes.
- **Text** - "A resource consisting primarily of words for reading"   
Examples include books, letters, dissertations, articles, archives of mailing lists. Note that facsimiles or images of texts are still of the genre Text.

### Simple Dublin Core Scheme

- *Contributor* – “An entity responsible for making contributions to the resource.”
- *Coverage* – “The spatial or temporal topic of the resource, the spatial applicability of the resource, or the jurisdiction under which the resource is relevant.”
- *Creator* – “An entity primarily responsible for making the resource.”
- *Date* – “A point or period of time associated with an event in the lifecycle of the resource.”
- *Description* – “An account of the resource.”
- *Format* – “The file format, physical medium, or dimensions of the resource.”
- *Identifier* – “An unambiguous reference to the resource within a given context.”
- *Language* – “A language of the resource.”
- *Publisher* – “An entity responsible for making the resource available.”
- *Relation* – “A related resource.”
- *Rights* – “Information about rights held in and over the resource.”
- *Source* – “A related resource from which the described resource is derived.”
- *Subject* – “The topic of the resource.”
- *Title* – “A name given to the resource.”
- *Type* – “The nature or genre of the resource.”

### Qualified Dublin Core Scheme

Some terms from the **Qualified Dublin Core** scheme will also be used in a particular way for each type of content. Below is a description of the **Qualified Dublin Core** scheme

- *abstract* - "A summary of the resource."
- *accessRights* - "Information about who access the resource or an indication of its security status."
- *accrualMethod* - "The method by which items are added to a collection."
- *accrualPeriodicity* - "The frequency with which items are added to a collection."
- *accrualPolicy* - "The policy governing the addition of items to a collection."
- *alternative* - "An alternative name for the resource."
- *audience* - "A class of agents for whom the resource is intended or useful."
- *available* - "Date that the resource became or will become available."
- *bibliographicCitation* - "A bibliographic reference for the resource."
- *conformsTo* - "An established standard to which the described resource conforms."
- *created* - "Date of creation of the resource."
- *dateAccepted* - "Date of acceptance of the resource."
- *dateCopyrighted* - "Date of copyright of the resource."
- *dateSubmitted* - "Date of submission of the resource."
- *educationLevel* - "Audience Education Level"
- *extent* - "The size or duration of the resource."
- *hasFormat* - "A related resource that is substantially the same as the pre-existing described resource, but in another format."
- *hasPart* - "A related resource that is included either physically or logically in the described resource."
- *hasVersion* - "A related resource that is a version, edition, or adaptation of the described resource."
- *instructionalMethod* - "A process, used to engender knowledge, attitudes and skills, that the described resource is designed to support."
- *isFormatOf* "A pre-existing related resource that is substantially the same as the described resource, but in another format."
- *isPartOf* "A related resource in which the described resource is physically or logically included."
- *isReferencedBy* - "A related resource that references, cites, or otherwise points to the described resource."
- *isReplacedBy* - "A related resource that supplants, displaces, or supersedes the described resource."
- *isRequiredBy* - "A related resource that requires the described resource to support its function, delivery, or coherence."
- *issued* - "Date of formal issuance of the resource."
- *isVersionOf* - "A related resource of which the described resource is a version, edition, or adaptation."
- *license* - "A legal document giving official permission to do something with the resource.""
- *mediator* - "An entity that mediates access to the resource."
- *medium* - "The material or physical carrier of the resource."
- *modified* - "Date on which the resource was changed."
- *provenance* - "A statement of any changes in ownership and custody of the resource since its creation that are significant for its authenticity, integrity, and interpretation."
- *references* - "A related resource that is referenced, cited, or otherwise pointed to by the described resource."
- *replaces* - "A related resource that is supplanted, displaced, or superseded by the described resource."
- *requires* - "A related resource that is required by the described resource to support its function, delivery, or coherence."
- *rightsHolder* - "A person or organization owning or managing rights over the resource."
- *spatial* - "Spatial characteristics of the resource."
- *tableOfContents* - "A list of subunits of the resource."
- *temporal* - "Temporal characteristics of the resource."
- *valid* - "Date (often a range) of validity of a resource."

More information on the **Dublin Core** terms at [https://www.dublincore.org/specifications/dublin-core/dcmi-terms/](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/)

## Metadata for LA-CoNGA Physics content

For each of the LA-CoNGA Physics contents, the **Simple Dublin Core** scheme will be used as a basis and this will be mandatory(*if apply*). In addition to the **Simple Dublin Core** metadata set, LA-CoNGA Physics content will have additional metadata from the **Quialified Dublin Core** schema(*if apply*). Additional metadata is defined below.

- abstract
- audience
- bibliographicCitation
- created
- dateSubmitted
- educationLevel
- extent
- isPartOf
- isVersionOf
- license
- modified
- requires
- rightsHolder

The LA-CoNGA Physics contents will be largely educational in nature, in order to better describe them for this scenario, the following metadata fields will be used.

- learningOutcome - "Expected learning outcomes when viewing the content"
- Keywords - "A set of keywords that describe the content and its topic"
- timeRequired - "The estimated time of dedication to analyze, interpret or work up the content"

The metadata described in this document will be the basis for all LA-ConGA Physics content, however, if it is required for a better description of any content, other metadata may be used. Additional Dublin Core metadata, metadata in other schemas or specific metadata (metadata associated with the status of some detector for example) can and should be used.

<!--
> Pendiente:
>
> - RDF para implementación
> - para agrupar https://www.dublincore.org/specifications/dublin-core/usageguide/qualifiers/
> -   - Indexed metadata
-->
