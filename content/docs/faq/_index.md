---
title: FAQs
summary: DMP4NFDI FAQs (part of documentation)
date: 2025-01-07
type: book

---    


## 🚀 Getting started with DMP4NFDI

### What is the National Research Data Infrastructure (NFDI)?

The NFDI is a non-profit association that aims to systematically manage scientific and research data, provide long-term data storage, backup and accessibility, and network the data both nationally and internationally. NFDI involves 26 consortia and one union of consortia, Base4NFDI.

### What is DMP4NFDI?

Funded and supported by Base4NFDI, DMP4NFDI is a centralised Basic Service supporting the development and provision of standardised Data and Software Management Plan services within the NFDI (DMP/SMP services). The service was initiated in May 2024 and is currently in the integration phase.

You can find more details here: [About DMP4NFDI](http:///about/dmp4nfdi/)

### What services does DMP4NFDI provide for NFDI?

DMP4NFDI supports NFDI consortia in developing and improving DMP or SMP Services for their research communities. Our services include:

- RDMO hosting for consortia  
- Support for RDMO integration with other services  
- Support for DMP & SMP template development and standardisation  
- Support for training and community outreach activities

You can explore our services in detail here: [DMP4NFDI Services](http:///services/)

## 💻 Getting started with RDMO in the NFDI

### What is RDMO?

The Research Data Management Organiser (RDMO) is an open-source DMP tool in productive use at many institutions in Germany for several years. It supports multiple DMP templates and its plugin architecture enables integrations with other services. RDMO has reached the status of a mature software with a big user community. To better satisfy the increasing demands and guarantee continuity and reliability, the non-profit RDMO association was founded on 19th November 2024\.

You can find more the details here: [About RDMO](http:///about/rdmo/)

### How does the RDMO hosting service provided by DMP4NFDI work?

DMP4NFDI hosts a multi-tenant RDMO instance. This makes it possible to add customised RDMO clients for each NFDI consortium. Our tasks include access management, roles and rights management, server management and maintenance, and general technical support for the consortia clients.

Learn more about our hosting service here: [RDMO hosting](http:///services/rdmo-hosting/)

### Why does each NFDI consortium have its own RDMO rather than one NFDI-RDMO instance?

DMP4NFDI hosts only one RDMO instance with different entry points, i.e. RDMO clients for each consortium. This allows consortia to provide a more customised service for their community, e.g. specific login mechanisms, theming, templates or plugins. Even in one domain, requirements for data management plans may vary considerably, so integrating all communities into one RDMO client would be rather complex to manage.

### Who can access the RDMO clients? Are they only for consortium members? 

While the hosting service is provided for NFDI consortia, the RDMO clients themselves are not restricted to consortium members. Researchers from outside the consortia can also access and use them.

An overview of productive RDMO clients is available here: [RDMO clients hosted by DMP4NFDI](https://dmp.services.base4nfdi.de/#hosting)

### How can I find the most suitable RDMO client for a multidisciplinary project?

You can find an overview of productive RDMO clients in NFDI here: [RDMO clients hosted by DMP4NFDI](https://dmp.services.base4nfdi.de/#hosting)

The range of DMP templates you can access depends on the RDMO client. We recommend getting in touch with the consortium that best fits your project and asking them for support. You will find their contact details in each RDMO client.

The [RDMO website](https://rdmorganiser.github.io/en/) also has an overview of all instances. You can find it by scrolling down a bit on the homepage.

### Is the RDMO community outside NFDI also aware of NFDI best practices and activities?

DMP4NFDI is actively involved in the RDMO community. We collect feedback, bugs and requirements from the consortia for further RDMO development and contribute them to the general RDMO roadmap.

## 🔄 RDMO Use and Interoperability

### Can RDMO be used to refine and update data management information as the project progresses (e.g. in connection with ELNs)?

Yes. RDMO can support the ongoing refinement of data management information throughout the project lifecycle.

Integrations with tools such as Electronic Lab Notebooks (ELNs) are actively being developed, for example in the context of OSTrails. In addition, existing and emerging plugins enable connections to other services.

RDMO also provides a REST API, which allows project-specific integrations and automated workflows to be implemented via scripts. Looking ahead, the increasing “machine-actionability” of DMPs will further support interoperability with other research tools and services.

### Once you have created your DMP, what can you do with RDMO? Is there some sort of management possible such as reminders to delete, publish or archive after project completion?

RDMO allows **integrations via plugins with other management tools** such as OpenProject or GitHub. The software also includes functions that help with data management such as:

- **Snapshots**: Allow to generate and save different versions of your DMP at specific times. If necessary, you can also reset your project to previous snapshots.  
- **Manage members**: You can invite other persons to work on the DMP and assign them different access rights (e.g. Guest, Author, Manager)  
- **Tasks**: They are generated automatically from the responses given in the project and help users remember important data management tasks.  
- **Import/Export**: You can import and export your RDMO project to create a local backup or to use it in other RDMO instances/clients. You can also export different versions of your DMP (e.g. as PDF).

### How does RDMO connect to ORCID or GitHub?

RDMO provides a REST API and a plugin architecture that enables flexible integration with other web services. Plugins are available for ORCID and GitHub.

You can find an overview of currently available RDMO plugins here: [RDMO Plugins](https://github.com/rdmorganiser/rdmo-plugins)

## 🏗️ Building a DMP service for your research community

### What does a DMP Service entail?

A DMP service should:

- **Run a community-specific RDMO client** where researchers can create DMPs, SMPs and work collaboratively  
- **Customise DMP or SMP templates** to meet the unique needs of your research community  
- **Offer training and outreach activities** focused on DMPs to help your community develop practical data and software management habits and adopt FAIR practices  
- **Connect RDMO with community services** to foster interoperability and smoother workflows

### What does running a community-specific RDMO client entail?

The NFDI consortium is responsible for operating the RDMO client. This involves managing and editing DMP or SMP templates, identifying community needs and adapting the templates to these needs. The consortium also advises and supports researchers in the use of RDMO for creating DMPs, e.g. through workshops, live demo sessions or other outreach activities that foster data and software management habits.

### What does customising DMP or SMP templates entail?

The NFDI consortium is responsible for identifying discipline-specific needs, for example through workshops, polls and interviews. Developing or adapting a template requires personnel with the necessary scientific background and knowledge of your discipline.

If you have already developed a DMP template tailored to the needs of your community, we recommend transferring the text-based template to RDMO.

If you have already created RDMO catalogs, we recommend revising and adapting them to align with the structure of the [NFDI DMP Template](http:///services/template-development/#nfdi-dmp-template-framework), which is in line with international standards. DMP4NFDI will support you throughout the process.

### How can I motivate researchers to use DMPs, SMPs and/or RDMO?

You can raise awareness of Data and Software Management Planning within your consortium by showcasing the value and benefits of using DMPs and RDMO through workshops, low-barrier introductory sessions, live demos, tailored presentations, and quick-start materials.

### I belong to an NFDI consortium and want to offer a DMP service to my research community. What should I do?

[Contact us\!](http:///contact/) For onboarding new consortia, we hold a regular call for [incubator projects](http:///incubator/), where we will together develop or improve your consortium's DMP or SMP service.

## 📄 Data Management Plans (DMPs) and machine-actionable DMPs (maDMP)

### Is there a central collection of DMPs somewhere (e.g. a Zenodo community)?

You can find examples on Zenodo, but we are not aware of a central DMP collection.

At the EU level, you can find many examples on the [CORDIS website](https://cordis.europa.eu/search?q=%27data%20management%20plan%27%20AND%20%2Fresult%2Frelations%2Fcategories%2Fcollection%2Fcode%3D%27deliverable%27&p=1&num=10&srt=Relevance:decreasing). This is the European Commission's main source of information on projects funded by the EU's research and innovation framework programmes.

### What does the maDMP look like in practice? Is there an example?

For RDMO, several plugins and integrations are available that enable metadata exchange between RDMO and other services. We are working with consortia use cases to develop and implement plugins and integrations.

- NFDI4Earth is connecting RDMO to sensor databases, collecting sensor metadata during the RDMO interview for inclusion in the DMP  
- MaRDI uses RDMO to add workflow information to their knowledge graph  
- In NFDI4ING, we are integrating the NFDI4ING Collections Explorer \- a catalog of repositories, data bases and resources  
- Together with NFDI4Biodiversity, we developed a plugin that allows DMPs to be published on Zenodo

A variety of RDMO plugins are already available: for connecting project management tools (e.g. OpenProject), querying data bases (e.g. ORCID, GND, Wikidata), or exporting metadata (e.g. as a CFF file for SMPs). When developing a template together with consortia, we also explore service integration options.

The maDMP is discussed at the international level, particularly within EOSC and the OSTrails project. For example, at TU Wien, the DAMAP DMP tool integrates the maDMP functionalities with their CRIS system or ORCID.  



<!-- 
**How can my consortium participate?**  
To access our service, your consortium needs to apply through one of our **Calls for Incubator Projects**. These calls are held two times per year, and consortia are invited to submit proposals outlining their specific project. 
Incubator projects:   
- Run for 3 - 6 months.  
- Have a clearly defined goal (e.g., setting up an RDMO client, developing a discipline-specific DMP template, integrating RDMO with other services, or training on DMPs and RDMO).  
- Require active collaboration, including providing your specific requirements for the DMP.

**What does DMP4NFDI’s hosting service offer?**  
We provide hosted RDMO clients that can be customised for each consortium, including:  
- A dedicated RDMO website with suitable  community AAI login.  
- Discipline-specific DMP templates (catalogs).  
- A shared database to allow cross-consortia collaboration
- Optional integrations with other consortium services (e.g., databases or registries).

**How does DMP4NFDI support knowledge transfer?**  
We develop:  
- **Train-the-Trainer (TTT) Workshops**: Equip research data managers with the skills to support their communities.  
- Comprehensive guides and FAQs for using RDMO and the developed templates.

**Who should attend TTT workshops?**  
Data stewards, research data managers, or anyone in your consortium responsible for supporting researchers with DMP creation.

**How can we promote RDMO in our community?**  
As part of our incubator projects, we help consortia:  
- Promote the use of RDMO.  
- Train key stakeholders.  
- Develop tailored communication strategies for their discipline.

## Getting started with Data Management Plans (DMPs)

**What is a Data Management Plan (DMP)?**  
A DMP is a structured document outlining how research data will be managed during and after a project. It covers areas like data collection, storage, sharing, long-term archiving, and ethical considerations, ensuring compliance with funder and institutional requirements. Various stakeholders have created DMP templates to guide the creation of a DMP.

**Why should I create a DMP?**  
A DMP helps you:  
- Organize and streamline your research data workflows.  
- Comply with funder requirements.  
- Enable data reuse within and beyond your research community.  

**Who creates and uses DMPs?**  
DMPs are typically created by researchers or research data managers at the start of a project and updated as needed. They are used to plan data workflows and to document decisions for compliance and transparency.


## Getting started with RDMO

**What is a DMP in RDMO?**  
In RDMO, a DMP template is called a "catalog." It is a template that structures the DMP creation process into sections and questions, helping researchers answer relevant data management aspects step-by-step. In order to create a DMP in RDMO, you create a project and select a suitable catalog for the interview.

**Can RDMO handle discipline-specific needs?**  
Yes! With the help of DMP4NFDI, consortia can develop discipline-specific DMP templates (catalogs) tailored to their community's requirements. Discipline-specific DMP templates and RDMOs are offered by various consortia, e.g. NFDI4ING, NFDI4Chem.

**How does DMP4NFDI support the development of these catalogs?**  
We work with consortia through focused **Incubator-Projects**. 
where we collaborate e.g., to 
- Identify the consortium's data management needs.  
- Develop a discipline-specific catalog (DMP template) in RDMO.  
- Train research data managers to implement and train their community in using the template. 

## DMP Services in the NFDI



