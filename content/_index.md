---
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    id: about
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: resume-skills
    id: skills
    content:
      title: Skills & Expertise
      username: me

  - block: resume-experience
    id: experience
    content:
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: false

  - block: collection
    id: projects
    content:
      title: Projects
      subtitle: ''
      filters:
        folders:
          - projects
    design:
      view: card

  - block: markdown
    id: creative
    content:
      title: Creative Lens
      subtitle: 'Between client calls and commits, I ride. Motorcycle touring across India has given me a lens — literal and figurative — on landscapes, people, and quiet moments in between.'
      text: '{{< creative-gallery >}}'
    design:
      columns: '1'

  - block: resume-awards
    id: certifications
    content:
      title: Certifications
      username: me

  - block: markdown
    id: contact
    content:
      title: Get In Touch
      subtitle: ''
      text: '{{< contact-form >}}'
    design:
      columns: '2'
---
