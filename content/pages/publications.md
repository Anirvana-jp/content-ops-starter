---
type: PageLayout
title: Publications
sections:
  - type: CarouselSection
    items:
      - type: FeaturedItem
        title: Peer-reviewed Journal Publications
        tagline: Feature 1
        subtitle: ''
        text: >+
          *   **Chakraborty A**, Goto H, & Sawada S (2023). Updating proxy-based
          site amplification map with in-situ data in Osaka, Japan: A Bayesian
          scheme based on Uncertainty Projected Mapping. *Earthquake Spectra*,
          40(1), 113-142.


          *   **Chakraborty A**, & Goto H (2020). Visualizing data saturation
          process in mapping site amplification of earthquake ground motions.
          *Journal of Natural Disaster Science*, 40(2), 14-25.


          *   **Chakraborty A**, & Goto H (2018). A Bayesian model reflecting
          uncertainties on map resolutions with application to the study of site
          response variation. *Geophysical Journal International*, 214(3),
          2264-2276.


          *   Eguchi, H, Goto H, Kurima J, & **Chakraborty A** (2023).
          Comparisons with site amplifications and S-wave impedance of the
          uppermost surface layer at Soma city. Special Issue (Earthquake
          Engineering) Technical Report, *Japanese Journal of JSCE*, 79(13),
          22-13041. (**Japanese**)


          *   Goto H, & **Chakraborty A** (2022). Visualizing spatial
          probability fields reflecting significant differences in neighboring
          values. *Japan Society of Civil Engineering proceedings A1
          (Structural/Earthquake Engineering)*,78(4), I-79-I-86. (**Japanese**)


          *   **Chakraborty A**, Ibrahim A, & Cruz AM (2018) A study of accident
          investigation methodologies applied to the Natech events during the
          2011 Great East Japan earthquake. *Journal of Loss Prevention in
          Process Industries*, 51, 208-222.

        image:
          type: ImageBlock
          altText: Featured item
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
    variant: tabs-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Generic Section With A Form
      color: text-dark
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      type: Badge
      label: Contact Us
      color: text-primary
    colors: bg-light-fg-dark
slug: /publications
isDraft: false
seo:
  type: Seo
  metaTitle: Landing Page
  metaDescription: Write here your new page's description including most relevant keywords.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
