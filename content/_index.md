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
          - "puteril"
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
        color:
          light: "#fafafa"
          dark: "#0a0a0f"
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
            FuRIA construcción de Tecnología IA feminista junto a Trabajadoras Sexuales Trans en Ecuador.
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["0rem", 0, 0, 0]

  - block: people
    id: organizers
    content:
      title: Equipa
      text: "Fundación FuRIATrans - Observatorio de Plataformas - CNRS"
      user_groups: ['Equipa']
    design:
      show_role: true
      show_social: false
      show_interests: false

  # - block: collection
  #   content:
  #     title: 'Événements Récents'
  #     count: 1
  #     sort_by: Params.event_start
  #     sort_ascending: false
  #     filters:
  #       folders:
  #         - events        
  #   design:
  #     view: card # card, article-grid

  - block: cta-card
    id: contact
    content:
      title: "Contáctanos"
      text: "¿Tienes preguntas?"
      button:
        text: "Send Email"
        url: "mailto:furia.tecnologiatravesti@framagroupes.org"
    design:
      card:
        # Card background color (CSS class)
        # css_class: 'bg-primary-900 dark:bg-primary-900'
        css_style: ''    
      background:
        # color: "blue-600"
        text_color_light: true
      spacing:
        padding: ["6", "6", "6", "6"]


  # # Contact Section
  # - block: contact-info
  #   id: contact
  #   content:
  #     title: Contactez-nous
  #     subtitle: ""
  #     text: 'Vous avez une question ?'
  #     email: coda-madics-pi@groupes.renater.fr
  #     autolink: false
  #   design:
  #     columns: '1'
  #     background:
  #       color:
  #         light: "#ffffff"
  #         dark: "#0d0d12"
  #     spacing:
  #       padding: ["4rem", "0", "4rem", "0"]        

---
