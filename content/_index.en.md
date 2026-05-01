---
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: "Keiichi Ishizu"
      text: "Geophysicist & Earth Scientist"
    design:
      background:
        image:
          filename: lake.jpg
          filters:
            brightness: 0.4
        image_size: cover
        image_position: center
      spacing:
        padding: ["12rem", "0", "12rem", "0"]

  - block: resume-biography-3
    content:
      username: admin
      text: 'Assistant Professor at Kyushu University (from Dec. 2024). Specializes in electromagnetic (EM) exploration using electromagnetic induction. Research focuses on geothermal resources, seafloor massive sulfides, and volcanic structures. Developing EM monitoring methods using controlled sources and a novel drone-based EM survey system.'
      button:
        text: 'View CV'
        url: cv/
      headings:
        about: ''
        education: 'Education'
        interests: 'Research Interests'
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        I specialize in **electromagnetic (EM) exploration** — geophysical imaging of subsurface structures without drilling. My primary targets are **geothermal resources, seafloor massive sulfides, and volcanic structures**.

        I am actively developing **EM monitoring methods using controlled artificial sources** (enabling eruption precursor detection, geothermal reservoir monitoring, CO₂ sequestration monitoring) and a novel **drone-mounted EM survey system** to overcome access restrictions in volcanic and geothermal regions.

        Feel free to reach out for collaborations or inquiries.
    design:
      columns: '1'

  - block: collection
    id: news
    content:
      title: 'Topics & News'
      text: ''
      filters:
        folders:
          - news
        limit: 5
    design:
      view: compact
      columns: '1'
---
