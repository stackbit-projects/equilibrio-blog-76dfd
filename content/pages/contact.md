---
title: Contáctanos
img_path: images/contact.jpg
form_id: contactForm
form_action: /success
form_fields:
  - input_type: text
    name: nameTu nomb
    label: Nombre
    default_value: Your name
    is_required: true
  - input_type: email
    name: email
    label: Correo electrónico
    default_value: Your email address
    is_required: true
  - input_type: select
    name: subject
    label: Asunto
    default_value: Selecciona uno
    options:
      - Enviar felicitaciones
      - Poner una queja
      - Otro
  - input_type: textarea
    name: message
    label: Mensaje
    default_value: Your message
  - input_type: checkbox
    name: consent
    label: >-
      Entiendo que este formulario almacena mi información enviada para así
      poder ser contactado.
submit_label: Enviar
seo:
  title: Get in Touch
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Get in Touch
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'og:image'
      value: images/contact.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Get in Touch
    - name: 'twitter:description'
      value: This is the contact page
    - name: 'twitter:image'
      value: images/contact.jpg
      relativeUrl: true
layout: contact
---
Por favor diligencia el siguiente formulario
