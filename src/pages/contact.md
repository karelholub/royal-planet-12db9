---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: gray
    title: Contact
    content: >-
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam a metus
      quis lorem malesuada luctus. Cras lacinia, eros at dapibus molestie, risus
      tortor pretium ligula.

      ##Kontaktní adresa

      **COPY GENERAL s.r.o.**
      Křížová 2598/4
      150 00 Praha 5

      tel.: +420 210 219 000
      (v pracovní dny od 8–17 hodin)
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Jméno a příjmení
        is_required: true
      - input_type: email
        name: email
        label: Email
        is_required: true
      - input_type: select
        name: subject
        label: Co vás zajímá
        default_value: Prosím vyberte
        options:
          - Chci interaktivní portál
          - Chci více informací
          - Mám obecný dotaz
      - input_type: textarea
        name: message
        label: Zpráva
      - input_type: checkbox
        name: consent
        label: >-
          Vyplněním a odesláním formuláře potvrzujete, že jste byli informováni o zpracování a ochraně osobních údajů v souladu s GDPR.
        is_required: true
    submit_label: Odeslat
template: landing
---
