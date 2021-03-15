# Metadatos Contenidos LA-CoNGA

Los contenidos creados en las actividades LA-CoNGA estarán definidos en un marco de ciencia abierta, el acceso abierto a estos será indispensable y se desarrollarán acciones para que los mismos cumplan con los principios [FAIR](https://www.go-fair.org/fair-principles/). Se usará el esquema de metadatos **Dublin Core** para describir los contenidos creados.

> Los contenidos de otras instituciones/proyectos usados en las actividades laconga serán tratados de acuerdos a las directrices dadas por la institución/proyecto creador.

En una primera etapa los contenidos definidos como productos LA-CoNGA y enmarcados en el vocabulario **Dublin Core** son:

> Por depurar  

- Collection - "An aggregation of resources"  
A collection is described as a group; its parts may also be separately described.
- Dataset - "Data encoded in a defined structure"  
Examples include lists, tables, and databases. A dataset may be useful for direct machine processing.
- Event - "A non-persistent, time-based occurrence"  
Comment 	Metadata for an event provides descriptive information that is the basis for discovery of the purpose, location, duration, and responsible agents associated with an event. Examples include an exhibition, webcast, conference, workshop, open day, performance, battle, trial, wedding, tea party, conflagration.
- Image - "A visual representation other than text"  
Examples include images and photographs of physical objects, paintings, prints, drawings, other images and graphics, animations and moving pictures, film, diagrams, maps, musical notation. Note that Image may include both electronic and physical representations.
- InteractiveResource - "A resource requiring interaction from the user to be understood, executed, or experienced"  
Examples include forms on Web pages, applets, multimedia learning objects, chat services, or virtual reality environments.
- MovingImage - "A series of visual representations imparting an impression of motion when shown in succession"  
Examples include animations, movies, television programs, videos, zoetropes, or visual output from a simulation. Instances of the type Moving Image must also be describable as instances of the broader type Image.
- PhysicalObject - "An inanimate, three-dimensional object or substance"  
Note that digital representations of, or surrogates for, these objects should use Image, Text or one of the other types.
- Service - "A system that provides one or more functions"  
Examples include a photocopying service, a banking service, an authentication service, interlibrary loans, a Z39.50 or Web server.
- Software - "A computer program in source or compiled form"  
Examples include a C source file, MS-Windows .exe executable, or Perl script.
- Sound - "A resource primarily intended to be heard"  
Examples include a music playback file format, an audio compact disc, and recorded speech or sounds.
- StillImage - "A static visual representation"  
Examples include paintings, drawings, graphic designs, plans and maps. Recommended best practice is to assign the type Text to images of textual materials. Instances of the type Still Image must also be describable as instances of the broader type Image.
- Text - "A resource consisting primarily of words for reading"  
Examples include books, letters, dissertations, poems, newspapers, articles, archives of mailing lists. Note that facsimiles or images of texts are still of the genre Text.

Para cada uno de estos contenidos se usará como base el esquema **Simple Dublin Core**. Este esquema esta constituido por los siguientes términos y serán de uso "obligatorio":

- Contributor – “An entity responsible for making contributions to the resource.”
- Coverage – “The spatial or temporal topic of the resource, the spatial applicability of the resource, or the jurisdiction under which the resource is relevant.”
- Creator – “An entity primarily responsible for making the resource.”
- Date – “A point or period of time associated with an event in the lifecycle of the resource.”
- Description – “An account of the resource.”
- Format – “The file format, physical medium, or dimensions of the resource.”
- Identifier – “An unambiguous reference to the resource within a given context.”
- Language – “A language of the resource.”
- Publisher – “An entity responsible for making the resource available.”
- Relation – “A related resource.”
- Rights – “Information about rights held in and over the resource.”
- Source – “A related resource from which the described resource is derived.”
- Subject – “The topic of the resource.”
- Title – “A name given to the resource.”
- Type – “The nature or genre of the resource.”

Se usará también algunos términos del esquema **Qualified Dublin Core** de manera partícular a cada tipo de contenido.

- abstract - "A summary of the resource."
- accessRights - "Information about who access the resource or an indication of its security status."
- accrualMethod - "The method by which items are added to a collection."
- accrualPeriodicity - "The frequency with which items are added to a collection."
- accrualPolicy - "The policy governing the addition of items to a collection."
- alternative - "An alternative name for the resource."
- audience - "A class of agents for whom the resource is intended or useful."
- available - "Date that the resource became or will become available."
- bibliographicCitation - "A bibliographic reference for the resource."
- conformsTo - "An established standard to which the described resource conforms."
- created - "Date of creation of the resource."
- dateAccepted - "Date of acceptance of the resource."
- dateCopyrighted - "Date of copyright of the resource."
- dateSubmitted - "Date of submission of the resource."
- educationLevel - "Audience Education Level"
- extent - "The size or duration of the resource."
- hasFormat - "A related resource that is substantially the same as the pre-existing described resource, but in another format."
- hasPart - "A related resource that is included either physically or logically in the described resource."
- hasVersion - "A related resource that is a version, edition, or adaptation of the described resource."
- instructionalMethod - "A process, used to engender knowledge, attitudes and skills, that the described resource is designed to support."
- isFormatOf "A pre-existing related resource that is substantially the same as the described resource, but in another format."
- isPartOf "A related resource in which the described resource is physically or logically included."
- isReferencedBy - "A related resource that references, cites, or otherwise points to the described resource."
- isReplacedBy - "A related resource that supplants, displaces, or supersedes the described resource."
- isRequiredBy - "A related resource that requires the described resource to support its function, delivery, or coherence."
- issued - "Date of formal issuance of the resource."
- isVersionOf - "A related resource of which the described resource is a version, edition, or adaptation."
- license - "A legal document giving official permission to do something with the resource.""
- mediator - "An entity that mediates access to the resource."
- medium - "The material or physical carrier of the resource."
- modified - "Date on which the resource was changed."
- provenance - "A statement of any changes in ownership and custody of the resource since its creation that are significant for its authenticity, integrity, and interpretation."
- references - "A related resource that is referenced, cited, or otherwise pointed to by the described resource."
- replaces - "A related resource that is supplanted, displaced, or superseded by the described resource."
- requires - "A related resource that is required by the described resource to support its function, delivery, or coherence."
- rightsHolder - "A person or organization owning or managing rights over the resource."
- spatial - "Spatial characteristics of the resource."
- tableOfContents - "A list of subunits of the resource."
- temporal - "Temporal characteristics of the resource."
- valid - "Date (often a range) of validity of a resource."

Más información de los términos **Dublin Core** en [https://www.dublincore.org/specifications/dublin-core/dcmi-terms/dcmitype/Image/](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/dcmitype/Image/)

A continuación se define para cada tipo de contenido los metadatos *Qualified Dublin Core* adicionales.

- Collection
  - abstract
  - accessRights
  - accrualMethod
  - accrualPeriodicity
  - accrualPolicy
  - alternative
  - audience
  - available
  - bibliographicCitation
  - conformsTo
  - contributor
  - coverage
  - created
  - creator
  - date
  - dateAccepted
  - dateCopyrighted
  - dateSubmitted
  - description
  - educationLevel
  - extent
  - format
  - hasFormat
  - hasPart
  - hasVersion
  - identifier
  - instructionalMethod
  - isFormatOf
  - isPartOf
  - isReferencedBy
  - isReplacedBy
  - isRequiredBy
  - issued
  - isVersionOf
  - language
  - license
  - mediator
  - medium
  - modified
  - provenance
  - publisher
  - references
  - relation
  - replaces
  - requires
  - rights
  - rightsHolder
  - source
  - spatial
  - subject
  - tableOfContents
  - temporal
  - title
  - type
  - valid
- Dataset
- Event
- Image
- InteractiveResource
- MovingImage
- PhysicalObject
- Service
- Software
- Sound
- StillImage
- Text

> Pendiente:
>
> - RDF para implementación
> - para agrupar https://www.dublincore.org/specifications/dublin-core/usageguide/qualifiers/
> -  Indexed metadata
