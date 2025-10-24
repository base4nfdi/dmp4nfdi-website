---
# Leave the homepage title empty to use the site title
title:
date: 2024-07-24
type: landing

sections:
  - block: hero
    content:
      title: |
            <span style="font-size: 3rem;">Data and Software Management Planning Services Across the NFDI</span>
            <br />
            <span style="color: #6c808099; font-size: 1.4rem;">funded and supported by the Base4NFDI initiative</span>
      image:
        filename: icon600x600.png
      text: |
        DMP4NFDI is a centralised Basic Service supporting the development and provision of standardised Data and Software Management Plan (DMP/SMP) services within the NFDI. We address critical infrastructure gaps by offering technical hosting of the open-source tool RDMO, specialised support for DMP/SMP template development, RDMO service integration, and targeted training.

        {{% cta cta_link="./about/" cta_text="Read more →" %}}
  
  - block: markdown
    content:
      title: Our Services
      subtitle: DMP4NFDI supports NFDI consortia by providing services aligned to Data and Software Management Plans
      text: |
        <div style="text-align:center;">

         **[RDMO hosting for consortia](#hosting)**  
         **[DMP & SMP template development](#template)**  
         **[Train-the-Trainer & Community Outreach](#training-outreach)**  
         **[RDMO integration with NFDI service portfolio](#rdmo-integration)** 

        </div>
    design:
      columns: '1'

  - block: markdown
    id: hosting
    content:
      title: RDMO Hosting for Consortia
      # subtitle:
      text: |
        We provide RDMO hosting for NFDI consortia through a multi-tenant RDMO instance. This setup allows each consortium to have a customised RDMO client, while still enabling the exchange of DMP templates and modules across the NFDI.

        [Read more →](/services/rdmo-hosting/) 
    design:
      columns: '2'

  - block: markdown
    id: template
    content:
      title: DMP & SMP template development
      text: |
        We provide guidance and support to NFDI consortia in using RDMO to create and customise catalogs and templates that meet their community’s specific needs and align with the NFDI DMP Template.

        [Read more →](/services/template-development/) 
    design:
      columns: '2'

  - block: markdown
    id: training-outreach
    content:
      title: Train-the-Trainer & Community Outreach 
      text:  |
        We offer Train-the-Trainer workshops on DMPs and RDMO, along with comprehensive training materials and tailored support to help you design and deliver effective training activities. In addition, we support community outreach to raise awareness and promote the adoption of DMPs, SMPs, and RDMO within your NFDI consortium.

        [Read more →](/services/training-outreach/)
    design:
      columns: '2'

  - block: markdown
    id: rdmo-integration
    content:
      title: RDMO Integration with NFDI Service Portfolio
      text:  |
        RDMO can connect seamlessly with many tools your consortium already uses, such as repositories, registries, or helpdesks. We provide integration support and help you link these systems with RDMO via API.
        
        [Read more →](/services/rdmo-integration/) 
    design:
      columns: '2'  
 
 
 # TODO here also other services could be linked which you provide, e.g. a hub or the documentation
  
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 3
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #       folders:
  #         - news
  #     offset: 0
  #     order: desc
  #   design:
  #     view: card
  #     columns: '1'

  #- block: collection
  #  content:
  #    title: Latest Publications
  #    text: ""
  #    count: 5
  #    filters:
  #      folders:
  #        - publications
  #      #publication_type: 'article'
  #  design:
  #    view: list
  #    columns: '1'

 # - block: markdown
   # content:
   #   title:
   #   subtitle:
   #   text: |
   #     {{% cta cta_link="./people/" cta_text="Meet the team →" %}} {{% cta cta_link="./contact/" cta_text="Contact us →" %}}
   # design:
   #   columns: '1'
---