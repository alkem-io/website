---
type: landing

url: /contact

sections:

  - block: markdown
    content:
      title: 
      subtitle:
      text: |-
        <div class="container">
        <div class="row">
          <div class="col-sm m-auto">  

          ## We would love to hear from you!

          {{< figure src="contactimage.webp" >}}

          </div>
          <div class="col-sm mt-4">  
          
          <script charset="utf-8" type="text/javascript" src="//js-eu1.hsforms.net/forms/embed/v2.js"></script>
          <script>
            hbspt.forms.create({
            portalId: "144061301",
            formId: "57dc58c6-1031-44c4-bc82-7ab85dcfc3cb",
            region: "eu1"
          });
          </script></div>  </div>  </div>
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      spacing:
        padding: [30px, 0px, 30px, 0px]

  - block: contact
    content:
      title: Contact
      subtitle:
      # Automatically link email and phone or display as text?
      autolink: true
      
      #phone: 888 888 88 88
      address:
        street: "Waldorpstraat 5"
        city: "The Hague"
        region: "South-Holland"
        postcode: "2521 CA"
        country: "The Netherlands"
        country_code: NL
      coordinates:
        latitude: '52.07931473185087'
        longitude: '4.341869769139752'
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      #appointment_url: 'https://calendly.com'
      email: info@alkem.io
      contact_links:
        - icon: building
          icon_pack: far
          name: Dutch KvK \#78302633
          link: 'https://www.kvk.nl/orderstraat/product-kiezen/?kvknummer=78302633'
        - icon: github
          icon_pack: fab
          name: Visit us on Github 
          link: 'https://github.com/alkem-io'
        - icon: linkedin
          icon_pack: fab
          name: Visit us on LinkedIn
          link: 'https://www.linkedin.com/company/alkemio-foundation/' 

    design:
      # Choose an optional background color, gradient, image, or video
      background:
        image:
          filename: #collaboration.png
          flip: false
        color: rgb(241, 244, 245)
      columns: '2'
      css_class: d-flex align-items-center
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: []

  - block: hero-custom
    content:
      title:
      # image:
      # Reference an image in your `assets/media/` folder
      # filename:
      cta:
        url: "https://alkem.io/identity/registration"
        label: Want to get started?
        # icon_pack: fas
        # icon: file-pdf

    design:
      columns: '1'
      css_class: centered-cta big-cta
      spacing:
        padding: ['20px', '0', '40px', '0']
      # Choose an optional background color, gradient, image, or video
      background:
        color: white


---
