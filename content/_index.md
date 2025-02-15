---
# Leave the homepage title empty to use the site title
title:
date: 2025-02-12
type: landing

sections:
  - block: hero
    content:
      title: |
        Interact Research Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The INTERACT Research Lab focuses on studying the structural integrity of interfaces and layered materials. Our research aims to understand failure mechanisms, improve durability, and develop innovative solutions to enhance material performance. By combining experimental methods with advanced monitoring techniques, numerical modeling, and biomimetic design, we address challenges in adhesive bonding, composite materials, and sustainable engineering solutions. 

        Here are the most recent topics studied in our lab: 

        Tailoring Composite Substrates: Exploring how modifying the stacking sequences of carbon fiber-reinforced polymer substrates can improve the damage tolerance of adhesively bonded joints. 

        Biomimetic Toughening Structures: Drawing inspiration from the molecular design of spider silk, the lab studies 3D-printed polymeric structures that incorporate sacrificial bonds and hidden lengths. When embedded in polymer resins, these structures enhance the toughness of layered materials and create a supporting framework that enables alternative load paths. 

        Characterization of Metal-to-Composite Interfaces: The integration of composites into traditional metal-based structures requires joining conventional metal parts with new composite materials. The lab has developed innovative methods for fracture characterization of bi-material bonded joints, with extensive expertise in metal-to-polymer interfaces. 

        Bio-Based Adhesives: In pursuit of sustainable bonding solutions, the lab explores adhesives derived from bio-renewable raw materials. Research includes the development and characterization of bio-based adhesives, aiming to replace conventional petroleum-based adhesives without compromising performance. 
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
