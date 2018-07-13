+++
date = 2017-01-01T00:00:00  # Schedule page publish date.

title = "Community Detection in Networks via Nonlinear Modularity Eigenvectors"
time_start = 2017-07-13
time_end = 2017-07-13
abstract = ""
abstract_short = ""
event = "SIAM minisymposium on Mathematics of large scale, time varying and higher-order networks at SIAM Annual Meeting (AN17)"
event_url = "http://www.siam.org/meetings/an17/"
location = "Pittsburgh, USA."

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["deep-learning"]

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

Community identification in networks is a central problem arising in many scientific areas. 
The modularity function $Q$ is an effective measure of the quality of a community, being
defined as a set of nodes having high modularity. 
Community detection thus boils down to the combinatorial optimization problem of locating sets of nodes maximizing $Q$.
This problem is known to be NP-hard thus posing the need of approximation techniques which are typically based on
a linear relaxation of $Q$, induced by the spectrum of the modularity matrix $\mathcal M$.

In this work we propose a nonlinear relaxation which is based on the spectrum of a nonlinear modularity operator $\mathcal M$. 
We show that extremal eigenvalues of $\mathcal M$
satisfy a tight Cheeger-type inequality providing
an exact relaxation of the modularity function $Q$,however
at a price of being more challenging to be computed than
the extremal eigenvalues of the linear counterpart based on $\mathcal M$. 
We propose a general optimization scheme for the computation of the extremal eigenvalues of $\mathcal M$,
named Generalized RatioDCA, and we show monotonic ascent and
convergence of the method to a critical value. Finally, we
present extensive evaluations on synthetic and real-world
datasets showing that our method is competitive to the
state of the art.

