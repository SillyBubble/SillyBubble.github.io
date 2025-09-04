---
# Leave the homepage title empty to use the site title
title:
date: 2025-07-12
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: ECCM21
        content: 21st European Conference on Composite Materials for Academia and Industry, Nantes
        align: left
        background:
          image:
            filename: ECCM21.jpg
            filters:
              brightness: 0.8
            size: contain
            position: right
          color: '#000000'
      - title: Lisboa Workshop 2025
        content: Advancements in Circular Design of Adhesively Bonded Joints & Toughening Strategies, Lisboa
        align: left
        background:
          image:
            filename: Lisboa.jpg
            filters:
              brightness: 0.8
            size: contain
            position: right
          color: '#000000'
      - title: AB2025
        content: 8th International Conference on Adhesive Bonding, Porto
        align: left
        background:
          image:
            filename: AB2025.jpg
            filters:
              brightness: 0.8
            size: contain
            position: right
          color: '#000'
      - title: AB2025
        content: 8th International Conference on Adhesive Bonding, Porto
        align: left
        background:
          image:
            filename: AB2025_view.jpg
            filters:
              brightness: 0.8
            size: contain
            position: right
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '500px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5000

  - block: hero
    content:
      title: ""
      image:
        filename: welcome.svg
      text: >
        The **INTERACT Research Lab** focuses on studying the structural integrity of interfaces and layered materials. Our research aims to understand failure mechanisms, improve durability, and develop innovative solutions to enhance material performance.  
    design:
      background:
        color: '#FFFFFF'
        text_color_light: false

  - block: markdown
    content:
      title: ""
      text: >
        <br>
        By combining experimental methods with advanced monitoring techniques, numerical modeling, and biomimetic design, we address challenges in adhesive bonding, composite materials, and sustainable engineering solutions. 
        Here are the most recent topics studied in our lab: 


        **Tailoring Composite Substrates**: Exploring how modifying the stacking sequences of carbon fiber-reinforced polymer substrates can improve the damage tolerance of adhesively bonded joints. 


        **Biomimetic Toughening Structures**: Drawing inspiration from the molecular design of spider silk, the lab studies 3D-printed polymeric structures that incorporate sacrificial bonds and hidden lengths. When embedded in polymer resins, these structures enhance the toughness of layered materials and create a supporting framework that enables alternative load paths. 


        **Characterization of Metal-to-Composite Interfaces**: The integration of composites into traditional metal-based structures requires joining conventional metal parts with new composite materials. The lab has developed innovative methods for fracture characterization of bi-material bonded joints, with extensive expertise in metal-to-polymer interfaces. 


        **Bio-Based Adhesives**: In pursuit of sustainable bonding solutions, the lab explores adhesives derived from bio-renewable raw materials. Research includes the development and characterization of bio-based adhesives, aiming to replace conventional petroleum-based adhesives without compromising performance. 
  
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text: |
        <div style="display:flex; flex-wrap:wrap; gap:5px; justify-content:center;">
          <img src="/images/ECCM21.jpg" width="450" />
          <img src="/images/Lisboa.jpg" width="450" />
          <img src="/images/AB2025.jpg" width="450" />
          <img src="/images/AB2025_view.jpg" width="450" />
        </div>
    design:
      columns: '1'
      class: fullscreen
    
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" style="text" %}}
    design:
      columns: '1'

---
