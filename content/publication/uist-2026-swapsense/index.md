---
#Basic Setting: draft - 해당 내용 안보이게; profile - 아래 author icon
#참고: https://docs.hugoblox.com/reference/page-features/#page-resources-attachments-and-links
draft: false ############# 
profile: true

title: 'SwapSense: Reusable Vision-Based Contact Force Sensing Across Swappable Passive Haptic Modules'
authors:
  - "Minha Jeon"
  - "Yeseo Park"
  - "Inhyuk Song"
  - "Yilong Lin"
  - "Seungwoo Je"
  - "Seungjae Oh"
author_notes:
  -
  - 
  -
  -
  -
  - "Corresponding Author"
date: '2026-11-02T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2026-05-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference-international']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 38th Annual ACM Symposium on User Interface Software and Technology*
publication_short: 'ACM UIST 2026'

abstract: The haptic qualities of physical interfaces—such as key-click sensations and stylus-tip stiffness—strongly shape user experience beyond functional performance. Prior work has explored reconfigurable passive structures to diversify such haptic experiences, but existing solutions typically sacrifice rich sensing capabilities or require dedicated sensing modules for each configuration. In this paper, we present SwapSense, a modular vision-based haptic I/O framework that physically decouples a shared sensing module from interchangeable haptic augmentation modules. A camera captures sequential deformation of a shared sensing substrate, and an encoder–decoder network estimates contact forces, while each attached augmentation module independently modulates force–displacement characteristics. Our results show that a model trained for pressing force estimation can generalize across users and support effective adaptation to previously unseen augmentation components. Owing to its modular AI architecture, the model efficiently adapts to unseen components with approximately 15 minutes of fine-tuning. A complementary perceptual study further shows that the five haptic augmentations span a perceptually diverse twodimensional perceptual space. Together, these results demonstrate that SwapSense enables reusable contact force sensing and perceptually expressive passive haptic reconfiguration within a single framework.

# Summary. An optional shortened abstract.
summary: .

tags:
  - Haptics
  - Sensing
  - ACM UIST
featured: true

links:
  - name: In Press
# url_pdf: https://lokilike.netlify.app/research/
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
