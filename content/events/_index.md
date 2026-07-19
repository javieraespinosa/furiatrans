---
title: Events
type: landing

sections:

  # - block: collection
  #   content:
  #     title: Focus
  #     count: 0
  #     sort_by: Params.event_start
  #     sort_ascending: false
  #     filters:
  #       folders:
  #         - events   
  #       featured_only: true     
  #   design:
  #     view: card # card, article-grid

  - block: collection
    content:
      title: Evénements
      count: 0
      sort_by: Params.event_start
      sort_ascending: false
      filters:
        folders:
          - events        
    design:
      view: article-grid # card, article-grid




  # - block: collection
  #   content:
  #     title: Recent & Upcoming Events
  #     filters:
  #       folders:
  #         - events
  #       exclude_past: true
  #     count: 2
  #     sort_ascending: false
  #     sort_by: Params.event_start
  #   design:
  #     view: card # article-grid      
---
