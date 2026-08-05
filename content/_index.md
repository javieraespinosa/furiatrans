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
      animations: false
      background:
        image:
          filename: bg.png
        text_color_light: false
        color:
          # light: "#fafafa"
          # dark: "#0a0a0f"
      spacing:
        padding: ["6rem", "0", "4rem", "0"]

  - block: logos
    content:
      # title: Instituciones
      # subtitle: Working with leading institutions worldwide
      # text: We collaborate with top universities and research centers
      logos:
        - name: FuriaTrans
          image: partners/logo_furiatrans.png
          url: https://www.instagram.com/fundacionfuriatrans/
          description: Fundación Furia Trans
        - name: ODP
          image: partners/logo_odp.png
          url: https://linktr.ee/ObservatorioDePlataformas
          description: Observatorio de Plataformas    
        - name: CNRS
          image: partners/logo_cnrs.png
          url: https://www.cnrs.fr/en
          description: Centro Nacional para la Investigación Científica
        - name: LIRIS
          image: partners/logo_liris.png
          url: https://liris.cnrs.fr
          description: Laboratorio de Procesamiento de Imágenes y Sistemas de Información
        - name: Lyon 1 Université
          image: partners/logo_lyon1.svg
          url: https://www.univ-lyon1.fr
          description: Lyon 1 Universidad Claude Bernard
        - name: UPPue
          image: partners/logo_uppue.png
          # url: https://www.uppuebla.edu.mx
          description: Universidad Politécnica de Puebla
    design:
      display_mode: grid # options: marquee
      css_class: "dark:bg-gray-900"
      show_pattern: true
      spacing:
        padding: ["1rem", "0", "1rem", "0"]


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
            furIA construcción de Tecnología IA feminista junto a Trabajadoras Sexuales Trans en Ecuador. <br>   
            
            ¡Conoce el proyecto!
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["0", 0, 0, 0]



  - block: cta-image-paragraph
    content:
      items:

        - title: "Presentación"
          text: >
            Presentamos furIA, Inteligencia Artificial feminista, diversa y comunitaria.
            Con desarrollo en Ecuador [Fundación Furia Trans] (https://www.instagram.com/fundacionfuriatrans/) y [Observatorio de Plataformas](https://www.linkedin.com/company/observatorio-de-plataformas-odp/posts/?feedView=all),  México Universidad de Politécnica de Puebla y Francia [Centro Nacional de la Investigación Científica](https://www.cnrs.fr/fr), la tecnología se co-crea junto a trabajadoras sexuales trans. Porque la IA también tiene que defender nuestros derechos. 
          image: authors/krus.jpg
          # feature_icon: hero/check-circle


        - title: "furIA: tecnología travesti"
          text: >
            furIA es una inteligencia artificial feminista, diversa y comunitaria, cocreada con trabajadoras sexuales trans en Ecuador. Nace de una pregunta: ¿cómo se ve la tecnología cuando la diseñan cuerpas atravesadas por el trabajo sexual y la resistencia trans?
            
            <br><br>

            furIA se amasa como una tecnología comunitaria, no como una herramienta extractivista. Parte de un principio fundamental: la tecnología no debe diseñarse para las comunidades, sino junto a ellas. Por eso el proyecto es co-coordinado desde el inicio entre la Fundación Furia Trans —primera organización liderada por mujeres trans trabajadoras sexuales en Ecuador— y el Observatorio de Plataformas, con el acompañamiento técnico de cientistas de datos e IA de México. Los fondos del proyecto los gestiona Furia Trans y las decisiones se toman en asamblea: el poder epistémico se redistribuye.

            <br><br>

            Pero más que un producto, furIA es un proceso: una investigación militante feminista y decolonial que rechaza la separación entre conocimiento y acción política. furIA es, entonces, un acto de desobediencia tecnológica: una semilla travesti para que el futuro se transforme.

          image: logo.png
          feature_icon: hero/check-circle
          # features:
          #   - Responsive images generated automatically
          #   - Markdown-first authoring
          #   - Works with Netlify, Vercel, and GitHub Pages
          # button:
          #   text: Read the guide
          #   url: /docs/get-started/

        - title: Objetivos 
          text: >

            <h3>¿Qué queremos construir?</h3>
            furIA responde a la falta de tecnología segura y diseñada desde las realidades trans y del trabajo sexual. Estamos desarrollando una plataforma con:
          feature_icon: hero/check-circle
          features:
            - Documentación y denuncia de vulneraciones de derechos humanos.
            - Mapa comunitario de emprendimientos.
            - Glosario trans inteligente, que preserva el lenguaje callejero.
            - "Directorio de apoyo legal, psicosocial y de autocuidado. Con esto buscamos visibilizar violencias invisibilizadas, fortalecer redes de apoyo y redistribuir el poder epistémico: la comunidad decide qué datos se recogen y cómo se usan."
          image: authors/ana.jpg

        - title: Iniciativa
          text: >
            Somos un proyecto en desarrollo de la red [IAfeminista](https://iafeminista.lat). La iniciativa incluye una plataforma para denunciar violaciones a los derechos humanos que permite documentar cuantitativamente esta problemática; un glosario trans construido a partir del lenguaje propio de la comunidad mediante técnicas de procesamiento de lenguaje natural (PLN); un directorio de servicios gratuitos de apoyo legal y psicosocial; guías y rutas para realizar denuncias; y recomendaciones comunitarias para el autocuidado y la defensa de los derechos.
          image: authors/pilar.jpg



  - block: team-showcase
    id: equipa
    content:
      title: Equipa
      # subtitle: > 
      #   Fundación FuRIATrans </br>        
      #   Observatorio de Plataformas </br>
      #   Universidad Politécnica de Puebla </br>
      #   CNRS-LIRIS
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
      # email: furia.tecnologiatravesti@proton.me
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
      form_action: https://formspree.io/f/xeajjnay
      
---
