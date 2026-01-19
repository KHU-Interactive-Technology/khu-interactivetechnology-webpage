---
#Basic Setting: draft - 해당 내용 안보이게; profile - 아래 author icon
#참고: https://docs.hugoblox.com/reference/page-features/#page-resources-attachments-and-links
draft: false 
profile: true

title: 'Item Selection through Context-Aware Gesture Understanding: Experimental Validation and Framework Proposal'
authors:
  - "Yeseo Park"
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

abstract: 가상현실과 증강현실 환경에서 제스처 인식은 직관적인 상호작용을 가능하게 하는 핵심 기술로 주목받아 왔다 그러나 기존 연구들은 주로 인식 정확도에 집중하여 실제 맥락을 반영한 의도 파악에는 한계가 있었다. 본 연구에서는 컨텍스트를 상황 요소(전투, 요리, 제작)로 정의하고, 이를 활용하여 사용자가 인벤토리 내 특정 아이템을 사용하는 제스처를 취했을 때, 보다 의도에 부합하는 아이템 자동 선택이 가능함을 검증한다. MediaPipe로 수집한 제스처 데이터를 활용해 동일한 모델 기반에서 컨텍스트 입력의 유무를 비교한 결과, 컨텍스트를 반영했을 때 아이템 선택의 정확도가 뚜렷하게 증가하였다. 이를 통해 컨텍스트가 제스처 기반 인터랙션의 정확성과 일관성에 기여함을 확인하였으며, 나아가 제스처 인코더와 컨텍스트 인코더를 결합한 소프트트리 기반 프레임워크를 제안한다.


# Summary. An optional shortened abstract.
# summary: In this study, we present SkinHaptics, a novel and device-free haptic methodology to facilitate self-haptic
# interactions through empirical evidence.

tags:
 - Context-Aware Gesture
#  - Physical AI
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
