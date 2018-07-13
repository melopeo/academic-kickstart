+++
title = "Clustering Signed Networks with the Geometric Mean of Laplacians"

# Date first published.
date = "2016-12-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Pedro Mercado", "Francesco Tudisco", "Matthias Hein"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *NIPS*"
publication_short = "In *NIPS*"

# Abstract and optional shortened version.
abstract = "Signed networks allow to model positive and negative relationships. We analyze existing extensions of spectral clustering to signed networks. It turns out that existing approaches do not recover the ground truth clustering in several situations where either the positive or the negative network structures contain no noise. Our analysis shows that these problems arise as existing approaches take some form of arithmetic mean of the Laplacians of the positive and negative part. As a solution we propose to use the geometric mean of the Laplacians of positive and negative part and show that it outperforms the existing approaches.  While the geometric mean of matrices is computationally expensive, we show that eigenvectors of the geometric mean can be computed efficiently, leading to a numerical scheme for sparse matrices which is of independent interest."
abstract_short = " "

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Links (optional).
url_pdf = "https://papers.nips.cc/paper/6164-clustering-signed-networks-with-the-geometric-mean-of-laplacians.pdf"
url_preprint = ""
url_code = "https://github.com/melopeo/GM"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "https://github.com/melopeo/GM/blob/master/PaperAndPoster/ClusteringSignedNetworksWithTheGeometricMeanOfLaplaciansPoster.jpg"
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]
url_custom = [{name = ".bib", url = "https://papers.nips.cc/paper/6164-clustering-signed-networks-with-the-geometric-mean-of-laplacians/bibtex"}, {name = "PDF (Supplement with proofs)", url = "https://papers.nips.cc/paper/6164-clustering-signed-networks-with-the-geometric-mean-of-laplacians-supplemental.zip"}]



# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption 😄"

+++


