---
title: "Temporal network embedding using
graph attention network
"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Anuraj Mohan
- K. V. Pramod

date: "2021-03-01T00:00:00Z"
doi: "https://doi.org/10.1007/s40747-021-00332-x"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Complex and intelligent systems (SCIE, IF 4.9), Springer *
publication_short: In  *Complex and intelligent systems (SCIE, IF 4.9), Springer*

abstract: Graph convolutional network (GCN) has made remarkable progress in learning good representations from graph-structured data. The layer-wise propagation rule of conventional GCN is designed in such a way that the feature aggregation at each node depends on the features of the one-hop neighbouring nodes. Adding an attention layer over the GCN can allow the network to provide different importance within various one-hop neighbours. These methods can capture the properties of static network, but is not well suited to capture the temporal patterns in time-varying networks. In this work, we propose a temporal graph attention network (TempGAN), where the aim is to learn representations from continuous-time temporal network by preserving the temporal proximity between nodes of the network. First, we perform a temporal walk over the network to generate a positive pointwise mutual information matrix (PPMI) which denote the temporal correlation between the nodes. Furthermore, we design a TempGAN architecture which uses both adjacency and PPMI information to generate node embeddings from temporal network. Finally, we conduct link prediction experiments by designing a TempGAN autoencoder to evaluate the quality of the embedding generated, and the results are compared with other state-of-the-art methods.

# Summary. An optional shortened abstract.
summary: In this work, we propose a temporal graph attention network (TempGAN), where the aim is to learn representations from continuous-time temporal network by preserving the temporal proximity between nodes of the network.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/content/pdf/10.1007/s40747-021-00332-x.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


---
