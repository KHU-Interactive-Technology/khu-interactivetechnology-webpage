---
#Basic Setting: draft - 해당 내용 안보이게; profile - 아래 author icon
#참고: https://docs.hugoblox.com/reference/page-features/#page-resources-attachments-and-links
draft: false 
profile: true

title: 'CrossGaussian: Enhancing Remote Collaboration through 3D Gaussian Splatting and Real-time 360° Streaming'
authors:
  - "Jaehyun Byun"
  - "Byunghoon Kang"
  - "Younghyun Gwon"
  - "Hongsong Choi"
  - "Seungjae Oh"
date: '2025-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2025-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['domestic-conference']

# Publication name and optional abbreviated publication name.
publication: Korean Institute of Information Scientists and Engineers
publication_short: 'KCC 2025'

abstract: 본 연구는 2D 디스플레이 기반 환경에서 현실과 가상 간의 입체적인 시각 경험과 자연스러운 전환 인터랙션을 제공하기 위한 새로운 시각화 기법을 제안한다. 먼저, Gaussian Splatting 기반의 고정밀 렌더링을 통해 현실 장면을 빠르게 3차원 환경으로 변환하고, 사용자 시점에 따라 동적으로 변하는 Motion Parallax 효과를 적용함으로써 2D 화면에서도 실감나는 공간감을 형성한다. 이를 위해 영상 입력만으로 자동 전처리를 수행하고 원격 서버 기반의 학습 파이프라인을 통해 복잡한 수작업 모델링 없이도 고품질의 3D 장면을 효율적으로 생성할 수 있도록 시스템을 구성하였다. 또한 실시간 시점 추적 정보를 기반으로 운동 시차에 따라 가상 카메라를 자동 조정하며 입체감을 형성하고 셰이더 기반 Dithering 기법을 활용해 여러 장면 간 전환에서  발생할  수있는  시각적  이질감을  최소화하였다.  본  연구는  착용형  장비  없이도  2D  디스플레이  환경에서 몰입감 높은 Cross Reality 경험을 제공할 수 있는 시각화 기법을 제안하며 원격 협업, 시뮬레이션 등 다양한 응용 분야와 깊이 지각이 유용한 상황에서의 확장 가능성을 지닌다.


# Summary. An optional shortened abstract.
# summary: In this study, we present SkinHaptics, a novel and device-free haptic methodology to facilitate self-haptic
# interactions through empirical evidence.

tags:
  - Remote Collaboration
  - Virtual Reality
  - 3D Gaussian Splatting
#  - Physical AI
#  - ACM CHI
featured: true

#links:
#  - name: Custom Link
#    url: https://lokilike.netlify.app/research/
url_pdf: https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12318659
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
