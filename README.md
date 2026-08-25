This thesis presents a novel approach to unsupervised extractive text summarization using hi-
erarchical transformer architectures. With the exponential growth of digital content, the need
for efficient text summarization methods has become increasingly critical. Our research ad-
dresses this challenge by combining the hierarchical bidirectional transformer architecture of
HIBERT with the unsupervised ranking criteria of STAS, enhanced by a Pointwise Mutual
Information (PMI)-based redundancy control mechanism. The proposed method employs
a two-level processing structure that captures both local sentence semantics and global docu-
ment structure. Unlike traditional approaches that rely on surface-level features, our hierar-
chical transformer architecture enables effective sentence-level attention mechanisms for rank-
ing sentences in unsupervised extractive summarization. The model processes documents by
generating contextual sentence representations through HIBERT’s pre-trained hierarchical en-
coder, then applies STAS ranking criteria combined with PMI-based redundancy measures to
select the most salient sentences. We evaluate our approach on the CNN/DailyMail dataset, a
standard benchmark for summarization tasks. The experimental results demonstrate that our
method achieves highly competitive performance, with significant improvements attributed to
the redundancy control mechanism.
