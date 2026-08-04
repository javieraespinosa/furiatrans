---
title: 'Inicio'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:

  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: "Trans + Trabajo Sexual + IA"
      show_status: false
      show_scroll_indicator: false
      typewriter:
        enable: true
        prefix: "Hacia una IA que huela a calle"
        strings:
          - "travesti"
          - " en resistencia"
          - "solidaria"
        type_speed: 70
        delete_speed: 30
        pause_time: 1500
      # cta_buttons:
      #   - text: View My Work
      #     url: "#projects"
      #     icon: arrow-down
      #   - text: Get In Touch
      #     url: "#contact"
      #     icon: envelope
    design:
      style: centered
      avatar_shape: circle
      animations: true
      background:
        image:
          # filename: bg-triangles.svg
          filename: bg.png
          filters:
            # brightness: 0          
        text_color_light: false
        color:
          # light: "#fafafa"
          # dark: "#0a0a0f"
      spacing:
        padding: ["6rem", "0", "4rem", "0"]


  - block: testimonials
    content:
      title: 
      text: 
      items:
        - name: ""
          role: ""
          # Upload image to `assets/media/` and reference the filename here
          image: ""
          text: > 
            furIA construcción de Tecnología IA feminista junto a Trabajadoras Sexuales Trans en Ecuador. ¡Conoce el proyecto!
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["0rem", 0, 0, 0]



  # - block: people
  #   id: organizers
  #   content:
  #     title: Equipa
  #     text: "Fundación FuRIATrans - Observatorio de Plataformas - CNRS"
  #     user_groups: ['Equipa']
  #   design:
  #     show_role: true
  #     show_social: false
  #     show_interests: false





  - block: team-showcase
    id: equipa
    content:
      title: Equipa
      subtitle: > 
        Fundación FuRIATrans </br>        
        Observatorio de Plataformas </br>
        Universidad Politécnica de Puebla </br>
        CNRS-LIRIS
      text: 
      user_groups:
        - Equipa
      sort_by: 'weight' # legacy 'Params.' prefix optional
      sort_ascending: true
      # cta:
      #   text: Join Our Team
      #   url: /opportunities
      #   icon: user-plus
    design:
      show_role: true
      show_organizations: true
      show_interests: true
      max_interests: 3   # set 0 to hide interests even if provided
      align: center      # or "left" to align header + CTA left
      max_columns: 3     # 2, 3, or 4
      show_social: true
      show_empty_groups: false # show a placeholder when a group has no members
      # Section background color (CSS class)
      css_class: "bg-gray-50 dark:bg-gray-900"





  - block: contact-info
    id: contact
    content:
      title: Escríbenos
      connect_title: "Contacto"
      subtitle: ""
      text: "Puedes escribirnos a:"
      # visit_title: Visit us
      # address:
      #   lines:
      #     - AI Lab, Engineering Building
      #     - 123 Innovation Way
      #     - Cambridge, MA
      # office_hours:
      #   - "Mon–Thu: 10:00–16:00"
      #   - "Fri: Remote"
      # map_url: https://maps.google.com/?q=Cambridge
      email: furia.tecnologiatravesti@proton.me
      # phone: +1 415 000 0000
      # social:
      #   - icon: brands/linkedin
      #     url: https://linkedin.com/company/hugoblox
      #   - icon: brands/x
      #     url: https://x.com/hugoblox
      # prospective:
      #   title: Prospective members
      #   text: Tell us about your research interests and links to prior work.
      #   button:
      #     text: Apply
      #     url: /apply
      show_form: true
      form_action: https://formspree.io/f/example 


  # - block: logos
  #   content:
  #     title: Our Partners & Collaborators
  #     subtitle: Working with leading institutions worldwide
  #     text: We collaborate with top universities and research centers
  #     logos:
  #       - name: MIT
  #         image: partners/mit.png
  #         url: https://mit.edu
  #         description: Massachusetts Institute of Technology
  #       - name: Stanford University
  #         image: partners/stanford.svg
  #         url: https://stanford.edu
  #         description: Leading research university
  #       - name: Google Research
  #         image: partners/google.png
  #         url: https://research.google
  #         description: AI and ML research
  #       - name: Microsoft Research
  #         image: partners/microsoft.svg
  #         url: https://www.microsoft.com/research
  #         description: Computing research lab
  #   design:
  #     display_mode: grid
  #     css_class: "bg-gray-50 dark:bg-gray-900"

---
