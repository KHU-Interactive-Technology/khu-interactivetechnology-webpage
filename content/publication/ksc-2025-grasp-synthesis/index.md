---
#Basic Setting: draft - 해당 내용 안보이게; profile - 아래 author icon
#참고: https://docs.hugoblox.com/reference/page-features/#page-resources-attachments-and-links
draft: false 
profile: true

title: 'Gaze-Conditioned Grasp Synthesis via 2D Segmentation and 3D Reconstruction'
authors:
  - "Yunseo Do"
  - "Seungjae Oh"
author_notes:
  -
  - "Corresponding Author"  
date: '2025-12-16T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-12-16T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['domestic-conference']

# Publication name and optional abbreviated publication name.
publication: Korean Institute of Information Scientists and Engineers
publication_short: 'KSC 2025'

abstract: 본 연구는 아이트래커를 통해 추출한 1인칭 시점 이미지(egocentric image)와 시선 좌표 정보(gaze point)를 조건으로 하여 사용자가 응시한 물체를 인식하고 3D로 복원한 뒤, 해당 객체에 대한 자연스러운 파지 자세 생성(grasp synthesis)을 수행하는 엔드투엔드 파이프라인을 제안한다. 기존 연구는 시선 정보를 로봇의 파지 대상 선택이나 행동 분류에 활용하는 데 그쳤으며, 이를 3D 복원 및 인간 손 기반 파지 생성까지 연결한 사례는 드물다. 본 연구는 시선 기반 2D 분할–3D 복원–파지 생성 단계를 하나의 흐름으로 통합하였으며, 사용자 평가에서 객체 선택 정확도, 분할 품질, 단계 간 물체 일관성에서 높은 타당성을 보였다. 이를 통해 시선 기반 조작 시스템의 새로운 가능성을 제시한다.


# Summary. An optional shortened abstract.
# summary: In this study, we present SkinHaptics, a novel and device-free haptic methodology to facilitate self-haptic
# interactions through empirical evidence.

tags:
  - Eye Tracking
  - 3D Reconstruction
#  - ACM CHI
featured: true

#links:
#  - name: Custom Link
#    url: https://lokilike.netlify.app/research/
# url_pdf: TBD
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
