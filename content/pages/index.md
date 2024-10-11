---
type: PageLayout
title: Home
colors: colors-b
backgroundImage:
  type: BackgroundImage
  url: /images/featured-Image5.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: 'olá sou o Daniel, GESTOR e programador de sistemas informáticos.'
    subtitle: >-
      Tenho 18 anos, sou de Famalicão e neste momento estudo na OFICINA - Escola
      Profissional no curso de Gestão e Programação de Sistemas Informáticos
      (GPSI) e aqui está um pouco dos meus trabalhos.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    media:
      type: ImageBlock
      url: /images/Design sem nome (1).png
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: EXPERIÊNCIA
    showFeaturedImage: false
    actions: []
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
  - type: LabelsSection
    title: Competências
    subtitle: ''
    items:
      - type: Label
        label: Hardware
        url: ''
      - type: Label
        label: Software
        url: ''
      - type: Label
        label: Manutenção de aplicações informáticas
        url: ''
      - type: Label
        label: Desenvolvimento web
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - type: MediaGallerySection
    title: Gallery
    subtitle: This is the subtitle
    images: []
    colors: colors-a
    spacing: 16
    columns: 5
    aspectRatio: '16:9'
    showCaption: true
    enableHover: false
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
---
