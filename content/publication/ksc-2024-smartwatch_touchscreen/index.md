---
#Basic Setting: draft - 해당 내용 안보이게; profile - 아래 author icon
#참고: https://docs.hugoblox.com/reference/page-features/#page-resources-attachments-and-links
draft: false 
profile: true

title: 'Classifying Body Parts and Hand Gestures Via Smartwatch Touchscreen'
authors:
  - "Jeongmin Lee"
  - "Seungjae Oh"
date: '2024-12-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['domestic-conference']

# Publication name and optional abbreviated publication name.
publication: Korean Institute of Information Scientists and Engineers
publication_short: 'KSC 2024'

abstract: 기술이 발달함에 따라 터치스크린 또한 성능이 향상되었지만 정작 실제로는 이 기능들을 제대로 활용하지 못하고 있다. 특히 이 문제는 크기가 너무 작아서 터치스크린으로 정확한 조작을 하기 힘든 스마트워치에서 빈번히 발생한다. 때문에 스마트워치 터치스크린을 통한 신체 부위와 손 제스처 판별 기술을 제안하여 터치 제스처의 확장을 기대하고자 한다. 해당 기술을 구현하기 위해 가공되지 않은 터치 데이터를 취득하였으며, 이를 위해 스마트워치 커널의 터치드라이버를 변형하였다. 이후 8개의 데이터 라벨에 대하여 총 2600여 개의 데이터를 수집하였으며, 이렇게 얻어진 데이터를 이용하여 합성곱 신경망을 학습시켰다. 학습시킨 모델은 89.4%의 정확도로 신체 부위와 손 제스처들을 구분하였다.


# Summary. An optional shortened abstract.
# summary: In this study, we present SkinHaptics, a novel and device-free haptic methodology to facilitate self-haptic
# interactions through empirical evidence.

tags:
 - Sensing Techniques
 - Physical AI
#  - ACM CHI
featured: true

#links:
#  - name: Custom Link
#    url: https://lokilike.netlify.app/research/
url_pdf: https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12042212
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
