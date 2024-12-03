---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "0rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:


  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Résumé
        url: uploads/CV_for_application_25_fall_yichizhang.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'


  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
      spacing:
        padding: "1rem"


  - block: awards
    content:
      title: Awards and Grants
      username: admin
    design:
      # Hugo date format
      date_format: '2006'


  - block: skills
    content:
      title: Technical Skills
      username: admin
    design:
      spacing:
        padding: "1rem"


---
