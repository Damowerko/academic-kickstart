---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Optimal Power Flow Using Graph Neural Networks"
authors: ["Damian Owerko", "Fernando Gama", "Alejandro Ribeiro"]
date: 2019-11-21
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Submitted for 45th IEEE International Conference on Acoustics, Speech and Signal Processing"
publication_short: "ICASSP 2020"

abstract: "
Optimal power flow (OPF) is one of the most important optimization problems in the energy industry. In its simplest form, OPF attempts to find the optimal power that the generators within the grid have to produce to satisfy a given demand. Optimality is measured with respect to the cost that each generator incurs in producing this power. The OPF problem is non-convex due to the sinusoidal nature of electrical generation and thus is difficult to solve. Using small angle approximations leads to a convex problem known as DC OPF, but this approximation is no longer valid when power grids are heavily loaded. Many approximate solutions have been since put forward, but these do not scale to large power networks. In this paper, we propose using graph neural networks (which are localized, scalable parametrizations of network data) trained under the imitation learning framework to approximate a given optimal solution. While the optimal solution is costly, it is only required to be computed for network states in the training set. During test time, the GNN adequately learns how to compute the OPF solution. Numerical experiments are run on the IEEE-30 and IEEE-118 test cases. 
"
# Summary. An optional shortened abstract.
summary: "In this paper, we propose using graph neural networks (which are localized, scalable parametrizations of network data) trained under the imitation learning framework to approximate a given optimal solution. While the optimal solution is costly, it is only required to be computed for network states in the training set. During test time, the GNN adequately learns how to compute the OPF solution. Numerical experiments are run on the IEEE-30 and IEEE-118 test cases."

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/abs/1910.09658"
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

