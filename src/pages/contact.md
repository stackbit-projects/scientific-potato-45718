---
title: Dime en que te puedo ayudar
img_path: images/contact.jpg
form_id: contactForm
form_action: /success
form_fields:
  - input_type: text
    name: name
    label: Nombre
    default_value: tu nombre
    is_required: true
  - input_type: email
    name: email
    label: Email
    default_value: tu correo electronico
    is_required: true
  - input_type: select
    name: subject
    label: Peticion
    default_value: Por favor seleciona
    options:
      - Soporte web
      - Consultoria
      - Sistemas de venta
      - Otro motivo
  - input_type: textarea
    name: message
    label: Se mas especifico
    default_value: dejame tu mensaje
  - input_type: checkbox
    name: consentimiento
    label: >-
      Entiendo que este formulario está almacenando mi información enviada para
      que puedan ser contactados.
submit_label: Enviar mensaje
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
template: contact
---
Te responderé lo más pronto posible
