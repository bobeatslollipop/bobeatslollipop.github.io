## About Me

I'm a fourth-year computer science PhD student in Northwestern University's [theory group](https://theory.cs.northwestern.edu/). My research interests lie in theoretical computer science and the foundations of machine learning. I study the capabilities and limitations of learning and computation, with a particular interest in how language models learn, memorize, and reason.

Before beginning my PhD studies at Northwestern University, I completed both my undergraduate and master's degrees at the same institution. (Go Cats!)

## Publications and Manuscripts

### Manuscripts

<div class="paper">
<span class="paper-title">Learning Rules, Memorizing Facts: An Information-Theoretic View of Hallucination</span>
<span class="paper-authors">Gengze Xu, <strong>Anxin Guo</strong>, Yifei Hu, Xiangyu Wu, Yong Liu, and Ziqiao Wang.</span>
<span class="paper-meta"><span class="venue">Preprint, 2026</span><span class="paper-links"><a href="https://arxiv.org/abs/2610.16233">arXiv</a></span></span>
</div>

<div class="paper">
<span class="paper-title">How Much Do You Trust A Dog? Quantifying Hint-Following in Reasoning Language Models</span>
<span class="paper-authors"><strong>Anxin Guo</strong>, Chirag Pabbaraju, Sara Ahmadian, Kamesh Munagala, and Aravindan Vijayaraghavan.</span>
</div>

<div class="paper">
<span class="paper-title">Regularized Transport Weights: a Principled Approach for Active Domain Adaptation</span>
<span class="paper-authors"><strong>Anxin Guo</strong>, Tanmay Sinha, Dionysis Arvanitakis, Vaidehi Srinivas, Alex Drlica-Wagner, Alexander Ji, and Aravindan Vijayaraghavan.</span>
</div>

<div class="paper">
<span class="paper-title">Leanify: Verified Proof Compression and Reusable Lemma Discovery</span>
<span class="paper-authors">Ruize Xu, <strong>Anxin Guo</strong>, Yi Gu, Tianchong Jiang, Chenxiao Yang, Tianhao Wang, and Zhiyuan Li.</span>
</div>

<div class="paper">
<span class="paper-title">Copying Under Repetition: From Prefix Matching to Position Hashing</span>
<span class="paper-authors"><strong>Anxin Guo</strong>, Tianlong Huang, Chenxiao Yang, and Zhiyuan Li.</span>
</div>

### Publications

<article class="paper">
<span class="paper-title" id="paper-hallucination">Hallucination is a Consequence of Space-Optimality: A Rate-Distortion Theorem for Membership Testing</span>
<span class="paper-authors"><strong>Anxin Guo</strong> and <a href="https://ieor.columbia.edu/content/jingwei-li">Jingwei Li</a>.</span>
<span class="paper-meta">
<span class="venue">ICML 2026</span>
<span class="badge">Spotlight · top 2.2%</span>
<span class="paper-links"><a href="https://arxiv.org/abs/2602.00906">arXiv</a><a href="https://icml.cc/virtual/2026/poster/60977">conference version</a><span class="paper-talk"><a href="https://www.youtube.com/watch?v=AVXfBUA8e-s" title="Oct 7, 2026; my segment: first ~10 minutes">student spotlight at Simons Institute</a><span class="talk-note">(my segment: first ~10 minutes)</span></span></span>
</span>
<details class="paper-abstract">
<summary aria-describedby="paper-hallucination">Summary</summary>

<p class="paper-summary">We model the memorization of random, non-inferable facts as a membership testing problem, connecting Bloom-filter-style error metrics with the log-loss behavior of language models. In the sparse-fact regime, we prove a rate-distortion theorem showing that the optimal space-error tradeoff is governed by a KL-divergence frontier. The result gives an information-theoretic explanation for high-confidence hallucinations: under limited capacity, even an optimal model may assign high confidence to some non-facts rather than simply abstaining or forgetting.</p>
</details>
</article>

<article class="paper">
<span class="paper-title" id="paper-relu">Agnostic Learning of Arbitrary ReLU Activation under Gaussian Marginals</span>
<span class="paper-authors"><strong>Anxin Guo</strong> and <a href="https://users.cs.northwestern.edu/~aravindv/">Aravindan Vijayaraghavan</a>.</span>
<span class="paper-meta">
<span class="venue">COLT 2025</span>
<span class="paper-links"><a href="https://arxiv.org/abs/2411.14349">arXiv</a><a href="https://proceedings.mlr.press/v291/guo25a.html">conference version</a><a href="https://youtu.be/bXVM10VRfcI?si=6dDID4kokQpQcaD2">recorded virtual talk</a></span>
</span>
<details class="paper-abstract">
<summary aria-describedby="paper-relu">Summary</summary>

<p class="paper-summary">We give the first algorithm for agnostic PAC learning of an arbitrarily biased ReLU neuron under Gaussian input distributions, up to constant approximation. We also prove a hardness separation between SQ (statistical query) and CSQ (correlational statistical query) models for this problem, showing a limitation of gradient-based algorithms in this setting.</p>
</details>
</article>

<article class="paper">
<span class="paper-title" id="paper-versioning">To Store or Not to Store: A Graph-Theoretic Approach for Dataset Versioning</span>
<span class="paper-authors"><strong>Anxin Guo</strong>, <a href="https://ieor.columbia.edu/content/jingwei-li">Jingwei Li</a>, <a href="https://pattaras.github.io/">Pattara Sukprasert</a>, <a href="https://www.mccormick.northwestern.edu/research-faculty/directory/profiles/khuller-samir.html">Samir Khuller</a>, <a href="https://www.cs.umd.edu/~amol/">Amol Deshpande</a>, and <a href="https://research.adobe.com/person/koyel-mukherjee/">Koyel Mukherjee</a>.</span>
<span class="paper-meta">
<span class="venue">IPDPS 2024</span>
<span class="paper-links"><a href="https://arxiv.org/abs/2402.11741">arXiv</a><a href="https://ieeexplore.ieee.org/document/10579114">conference version</a></span>
</span>
<details class="paper-abstract">
<summary aria-describedby="paper-versioning">Summary</summary>

<p class="paper-summary">We study a graph-theoretic framework for dataset versioning that optimizes storage costs while controlling retrieval costs across versions. On the theory side, we prove hardness-of-approximation results and give provably near-optimal algorithms for tree-like graphs of bounded treewidth. These results also lead to practical heuristics with up to 1000x speedups for the "MinSum Retrieval" problem on real-world GitHub repositories.</p>
</details>
</article>

## Selected Talks

<div class="entry">
<span class="entry-title">Hallucination and Space-Optimality</span>
<span class="entry-meta"><strong>Simons Institute</strong> &middot; Student spotlight, <a href="https://simons.berkeley.edu/workshops/trustworthy-ai-hallucinations-reliable-autonomy">Trustworthy AI: From Hallucinations to Reliable Autonomy</a> &middot; October 2026</span>
<span class="paper-links"><span class="paper-talk"><a href="https://www.youtube.com/watch?v=AVXfBUA8e-s">Video</a><span class="talk-note">(my segment: first ~10 minutes)</span></span></span>
<span class="entry-meta"><strong>Google AI Study Group</strong> &middot; Invited talk &middot; September 2026</span>
<span class="entry-meta"><strong>IDEAL Annual Meeting, TTIC</strong> &middot; Lightning talk &middot; September 2026</span>
</div>

<div class="entry">
<span class="entry-title">Intelligent Scheduling for Astronomical Surveys</span>
<span class="entry-meta"><strong>SkAI Works-In-Progress</strong> &middot; Joint presentation with Rachel Hur and Tanmay Sinha &middot; September 2026</span>
</div>

<div class="entry">
<span class="entry-title">Agnostically Learning Arbitrary ReLU Neurons</span>
<span class="entry-meta"><strong>IDEAL Annual Meeting, UIC</strong> &middot; Student talk &middot; June 2025</span>
<span class="entry-meta"><strong>Northwestern University</strong> &middot; CS Theory Seminar &middot; February 2025</span>
<span class="entry-meta"><strong>NSF TRIPODS Workshop, TTIC</strong> &middot; Lightning talk &middot; December 2024</span>
</div>

## Education

<div class="entry">
<span class="entry-title">Ph.D. student in Computer Science</span>
<span class="entry-meta">Northwestern University, Evanston, Illinois · 2023&ndash;present</span>
</div>

<div class="entry">
<span class="entry-title">B.A. in Math and M.S. in Computer Science</span>
<span class="entry-meta">Northwestern University, Evanston, Illinois · 2019&ndash;2023</span>
</div>

## Awards

- Ph.D. student research award (Northwestern CS department), _2024-2025_.
- [Barris Award for outstanding TA](https://www.mccormick.northwestern.edu/computer-science/news-events/news/articles/2025/northwestern-cs-announces-fall-2024-winter-2025-outstanding-teaching-assistants-and-peer-mentors.html), CS 335: Introduction to the Theory of Computing, _2024 Fall quarter_.
- Junior Career Award in Mathematics (Northwestern math department), _2021-2022_.

## Academic Activities

### Research and Teaching

- IDEAL-funded summer research exchange, University of Chicago, Summer 2026. Hosted by Prof. [Chao Gao](https://www.stat.uchicago.edu/~chaogao/).
- IDEAL-funded summer research exchange, Toyota Technological Institute at Chicago (TTIC), Summer 2025. Hosted by Prof. [Zhiyuan Li](https://zhiyuanli.ttic.edu/).
- Teaching Assistant, CS 336: Design and Analysis of Algorithms, _2026 Spring quarter_.
- Teaching Assistant, CS 335: Introduction to the Theory of Computing, _2024 Fall quarter_. Guest lecture on busy beaver numbers.

### Service and Programs

- Program Committee / Reviewer, [Reliable ML from Unreliable Data](https://reliablemlworkshop.github.io/), NeurIPS 2025 Workshop.
- Volunteer, [FOCS 2024](https://focs.computer.org/2024/) (65th IEEE Symposium on Foundations of Computer Science), Chicago, IL.
- Ross Mathematics Program (Asia): first-year student (2018), junior counselor (2019), counselor (2020).
- Directed Reading Program: Spring 2021, read _Linear Representations of Finite Groups_ with [Wenyuan Li](https://wenyuanli1995-math.github.io/).

## Miscellaneous

I have written three articles on 知乎 about theoretical computer science. Here is the [link](https://zhuanlan.zhihu.com/p/643661983).

<details>
<summary>More personal notes</summary>

<p>I grew up in Beijing and still have a soft spot for its subway system and shared bicycles.</p>

</details>
