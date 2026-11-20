## About Me

I'm a fourth-year computer science PhD student in Northwestern University's [theory group](https://theory.cs.northwestern.edu/). I'm very fortunate to be advised by <a class="person" href="https://users.cs.northwestern.edu/~aravindv/">Aravindan Vijayaraghavan</a>. My research interests lie in theoretical computer science and the foundations of machine learning.

Before beginning my PhD studies at Northwestern University, I completed both my undergraduate and master's degrees at the same institution. (Go Cats!)

## Publications and Manuscripts

### Publications

<article class="paper">
<span class="paper-title" id="paper-hallucination">Hallucination is a Consequence of Space-Optimality: A Rate-Distortion Theorem for Membership Testing</span>
<span class="paper-authors"><strong>Anxin Guo</strong> and <a href="https://ieor.columbia.edu/content/jingwei-li">Jingwei Li</a>.</span>
<span class="paper-meta">
<span class="venue is-published">ICML 2026</span>
<span class="badge">Spotlight</span>
<span class="paper-links"><button class="summary-toggle" type="button" aria-expanded="true" aria-controls="summary-hallucination" aria-describedby="paper-hallucination">Summary</button><a href="https://arxiv.org/abs/2602.00906">arXiv</a><a href="https://www.youtube.com/watch?v=AVXfBUA8e-s" title="Simons Institute spotlight, Oct 2026. My segment is the first ~10 minutes of the recording.">Video<span class="chip-note">first 10 min</span></a></span>
</span>
<p class="paper-summary" id="summary-hallucination">We model the memorization of random, non-inferable facts as a membership testing problem, connecting Bloom-filter-style error metrics with the log-loss behavior of language models. In the sparse-fact regime, we prove a rate-distortion theorem showing that the optimal space-error tradeoff is governed by a KL-divergence frontier. The result gives an information-theoretic explanation for high-confidence hallucinations: in this regime under log-loss, the limiting space-optimal solution assigns the same confidence to all facts and a nonzero fraction of non-facts, rather than simply abstaining or forgetting.</p>
</article>

<article class="paper">
<span class="paper-title" id="paper-relu">Agnostic Learning of Arbitrary ReLU Activation under Gaussian Marginals</span>
<span class="paper-authors"><strong>Anxin Guo</strong> and <a href="https://users.cs.northwestern.edu/~aravindv/">Aravindan Vijayaraghavan</a>.</span>
<span class="paper-meta">
<span class="venue is-published">COLT 2025</span>
<span class="paper-links"><button class="summary-toggle" type="button" aria-expanded="true" aria-controls="summary-relu" aria-describedby="paper-relu">Summary</button><a href="https://arxiv.org/abs/2411.14349">arXiv</a><a href="https://youtu.be/bXVM10VRfcI?si=6dDID4kokQpQcaD2">Video</a></span>
</span>
<p class="paper-summary" id="summary-relu">We give the first polynomial-time statistical query (SQ) algorithm for agnostic PAC learning of an arbitrarily biased ReLU neuron under Gaussian marginals, achieving a constant-factor approximation with any desired additive tolerance. Large negative biases are challenging because the neuron activates only in the Gaussian tail, where adversarial noise can overwhelm the informative gradient signal or even drive gradient descent in the wrong direction. Complementing our algorithm, we prove a hardness separation between general SQ and correlational SQ (CSQ), formalizing this limitation of gradient-based methods.</p>
</article>

<article class="paper">
<span class="paper-title" id="paper-versioning">To Store or Not to Store: A Graph-Theoretic Approach for Dataset Versioning</span>
<span class="paper-authors"><strong>Anxin Guo</strong>, <a href="https://ieor.columbia.edu/content/jingwei-li">Jingwei Li</a>, <a href="https://pattaras.github.io/">Pattara Sukprasert</a>, <a href="https://www.mccormick.northwestern.edu/research-faculty/directory/profiles/khuller-samir.html">Samir Khuller</a>, <a href="https://www.cs.umd.edu/~amol/">Amol Deshpande</a>, and <a href="https://research.adobe.com/person/koyel-mukherjee/">Koyel Mukherjee</a>.</span>
<span class="paper-meta">
<span class="venue is-published">IPDPS 2024</span>
<span class="paper-links"><button class="summary-toggle" type="button" aria-expanded="true" aria-controls="summary-versioning" aria-describedby="paper-versioning">Summary</button><a href="https://arxiv.org/abs/2402.11741">arXiv</a></span>
</span>
<p class="paper-summary" id="summary-versioning">We study a graph-theoretic framework for dataset versioning that optimizes storage costs while controlling retrieval costs across versions. On the theory side, we prove hardness-of-approximation results and give provably near-optimal algorithms for version graphs of bounded treewidth. On one real GitHub version graph, our dynamic programming heuristic achieved nearly three orders of magnitude lower total retrieval cost than the prior heuristic at comparable storage budgets.</p>
</article>

### Manuscripts

<article class="paper">
<span class="paper-title" id="paper-copying">Copying Under Repetition: From Prefix Matching to Position Hashing</span>
<span class="paper-authors"><strong>Anxin Guo</strong>, Tianlong Huang, <a href="https://chr26195.github.io/">Chenxiao Yang</a>, and <a href="https://zhiyuanli.ttic.edu/">Zhiyuan Li</a>.</span>
<span class="paper-meta">
<span class="venue">Preprint, 2026</span>
<span class="paper-links"><button class="summary-toggle" type="button" aria-expanded="true" aria-controls="summary-copying" aria-describedby="paper-copying">Summary</button><a href="https://arxiv.org/abs/2610.26722">arXiv</a></span>
</span>
<p class="paper-summary" id="summary-copying">Language models that copy random text accurately can still stop too early or too late on a long run of identical characters. We prove a limit for a class of finite-precision transformers and construct a two-layer transformer that uses periodic position codes (with small prime periods) to copy any string up to a chosen length and stop exactly at the end. In synthetic copying experiments, baselines with standard positional encodings such as RoPE struggled on long repeated strings even within the training range, while our model trained on strings up to 2,000 tokens generalized to 5,000 tokens with near-perfect accuracy.</p>
</article>

<article class="paper">
<span class="paper-title" id="paper-dog">How Much Do You Trust A Dog? Quantifying Hint-Following in Reasoning Language Models</span>
<span class="paper-authors"><strong>Anxin Guo</strong>, <a href="https://web.stanford.edu/~cpabbara/">Chirag Pabbaraju</a>, <a href="https://research.google/people/106920/">Sara Ahmadian</a>, <a href="https://www.kameshmunagala.org/">Kamesh Munagala</a>, and <a href="https://users.cs.northwestern.edu/~aravindv/">Aravindan Vijayaraghavan</a>.</span>
<span class="paper-meta">
<span class="venue">Preprint, 2026</span>
<span class="paper-links"><button class="summary-toggle" type="button" aria-expanded="true" aria-controls="summary-dog" aria-describedby="paper-dog">Summary</button><a href="https://arxiv.org/abs/2610.32055">arXiv</a></span>
</span>
<p class="paper-summary" id="summary-dog">How much does an external hint sway a reasoning language model's prior judgment? On multiple-choice questions, we find that for a given source, a hint gives the suggested answer a roughly constant average boost in log-odds across a wide range of starting probabilities, as if it carried a fixed evidence weight. In our tests, the boost was not calibrated to the source's stated reliability, and explicit distrust warnings weakened it without eliminating it.</p>
</article>

<article class="paper">
<span class="paper-title" id="paper-syzygies">Approximate Syzygies of Smoothed Polynomials and Applications</span>
<span class="paper-authors"><a href="https://users.cs.utah.edu/~bhaskara/">Aditya Bhaskara</a>, <strong>Anxin Guo</strong>, <a href="https://tanmaysinha18.github.io/">Tanmay Sinha</a>, <a href="https://vaidehi8913.github.io/">Vaidehi Srinivas</a>, and <a href="https://users.cs.northwestern.edu/~aravindv/">Aravindan Vijayaraghavan</a>.</span>
<span class="paper-meta">
<span class="venue is-draft">Manuscript</span>
<span class="paper-links"><button class="summary-toggle" type="button" aria-expanded="true" aria-controls="summary-syzygies" aria-describedby="paper-syzygies">Summary</button><a href="/assets/papers/approximate-syzygies.pdf">PDF</a></span>
</span>
<p class="paper-summary" id="summary-syzygies">A linear system can be sensitive to small errors when a combination of its columns almost cancels out. We study the same phenomenon for polynomials. After small random perturbations, we show that nearly canceling combinations are close to Koszul syzygies, simple exact cancellations that come from the fact that multiplication commutes. This answers an open question about efficiently decomposing a noisy sum of powers of polynomials in the smoothed setting <a href="https://arxiv.org/pdf/2208.00122#page=6">[BHKX22]</a>. We also establish robust uniqueness of symmetric third-order tensor decompositions at superlinear rank under small random perturbations, addressing an open question raised in <a href="https://proceedings.mlr.press/v35/bhaskara14a.pdf#page=3">[BCV14]</a>.</p>
</article>

<div class="paper">
<span class="paper-title">Regularized Transport Weights: a Principled Approach for Active Domain Adaptation</span>
<span class="paper-authors"><strong>Anxin Guo</strong>, <a href="https://tanmaysinha18.github.io/">Tanmay Sinha</a>, <a href="https://dion11ar.github.io/">Dionysis Arvanitakis</a>, <a href="https://vaidehi8913.github.io/">Vaidehi Srinivas</a>, <a href="https://kadrlica.github.io/">Alex Drlica-Wagner</a>, <a href="https://www.alexji.com/">Alexander Ji</a>, and <a href="https://users.cs.northwestern.edu/~aravindv/">Aravindan Vijayaraghavan</a>.</span>
<span class="paper-meta"><span class="venue is-draft">Manuscript</span></span>
</div>

<div class="paper">
<span class="paper-title">New Tools for Smoothed Analysis: Least Singular Value Bounds for Random Matrices with Dependent Entries</span>
<span class="paper-authors"><a href="https://users.cs.utah.edu/~bhaskara/">Aditya Bhaskara</a>, <a href="https://ericevert.com/">Eric Evert</a>, <strong>Anxin Guo</strong>, <a href="https://tanmaysinha18.github.io/">Tanmay Sinha</a>, <a href="https://vaidehi8913.github.io/">Vaidehi Srinivas</a>, and <a href="https://users.cs.northwestern.edu/~aravindv/">Aravindan Vijayaraghavan</a>.</span>
<span class="paper-meta"><span class="venue">Corrected and revised version, 2026</span><span class="paper-links"><a href="https://arxiv.org/abs/2405.01517v3">arXiv</a></span></span>
<span class="entry-meta">With Tanmay Sinha, I identified a gap in the earlier proof and helped develop a new proof of the main theorem. The original four-author version appeared in STOC 2024.</span>
</div>

<div class="paper">
<span class="paper-title">Leanify: Verified Proof Compression and Reusable Lemma Discovery</span>
<span class="paper-authors"><a href="https://cs.uchicago.edu/people/ruize-richard-xu/">Ruize Xu</a>, <strong>Anxin Guo</strong>, Yi Gu, <a href="https://tianchong-jiang.github.io/">Tianchong Jiang</a>, <a href="https://chr26195.github.io/">Chenxiao Yang</a>, <a href="https://tiiao.github.io/">Tianhao Wang</a>, and <a href="https://zhiyuanli.ttic.edu/">Zhiyuan Li</a>.</span>
<span class="paper-meta"><span class="venue is-draft">Manuscript</span></span>
</div>

<div class="paper">
<span class="paper-title">Learning Rules, Memorizing Facts: An Information-Theoretic View of Hallucination</span>
<span class="paper-authors">Gengze Xu, <strong>Anxin Guo</strong>, Yifei Hu, Xiangyu Wu, <a href="https://ai.ruc.edu.cn/GSAI_HOME/FACULTYn/YongLiu/423b52e166034e8a98a1ea3f6e090e83.htm">Yong Liu</a>, and <a href="https://ziqiaowanggeothe.github.io/">Ziqiao Wang</a>.</span>
<span class="paper-meta"><span class="venue">Preprint, 2026</span><span class="paper-links"><a href="https://arxiv.org/abs/2610.16233">arXiv</a></span></span>
</div>

## Selected Talks

<div class="entry">
<span class="entry-title">Hallucination and Space-Optimality</span>
<span class="dated"><span class="entry-meta"><strong>Simons Institute</strong> &middot; Student spotlight, <a href="https://simons.berkeley.edu/workshops/trustworthy-ai-hallucinations-reliable-autonomy">Trustworthy AI: From Hallucinations to Reliable Autonomy</a></span><span class="date">Oct 2026</span></span>
<span class="paper-links"><a href="https://www.youtube.com/watch?v=AVXfBUA8e-s" title="Simons Institute spotlight, Oct 2026. My segment is the first ~10 minutes of the recording.">Video<span class="chip-note">first 10 min</span></a></span>
<span class="dated"><span class="entry-meta"><strong>Google AI Study Group</strong> &middot; Invited talk</span><span class="date">Sep 2026</span></span>
<span class="dated"><span class="entry-meta"><strong>IDEAL Annual Meeting, TTIC</strong> &middot; Lightning talk</span><span class="date">Sep 2026</span></span>
</div>

<div class="entry">
<span class="entry-title">Intelligent Scheduling for Astronomical Surveys</span>
<span class="dated"><span class="entry-meta"><strong>SkAI Works-In-Progress</strong> &middot; Joint presentation with <a class="person" href="https://physics.uchicago.edu/people/profile/rachel-hur/">Rachel Hur</a> and <a class="person" href="https://tanmaysinha18.github.io/">Tanmay Sinha</a></span><span class="date">Sep 2026</span></span>
</div>

<div class="entry">
<span class="entry-title">Agnostically Learning Arbitrary ReLU Neurons</span>
<span class="dated"><span class="entry-meta"><strong>IDEAL Annual Meeting, UIC</strong> &middot; Student talk</span><span class="date">Jun 2025</span></span>
<span class="dated"><span class="entry-meta"><strong>Northwestern University</strong> &middot; CS Theory Seminar</span><span class="date">Feb 2025</span></span>
<span class="dated"><span class="entry-meta"><strong>NSF TRIPODS Workshop, TTIC</strong> &middot; Lightning talk</span><span class="date">Dec 2024</span></span>
</div>

## Education

<div class="entry">
<span class="dated"><span class="entry-title">Ph.D. student in Computer Science</span><span class="date">2023&ndash;present</span></span>
<span class="entry-meta">Northwestern University, Evanston, Illinois</span>
</div>

<div class="entry">
<span class="dated"><span class="entry-title">B.A. in Math and M.S. in Computer Science</span><span class="date">2019&ndash;2023</span></span>
<span class="entry-meta">Northwestern University, Evanston, Illinois</span>
</div>

## Awards

<ul class="dated-list">
<li><span>Ph.D. student research award (Northwestern CS department).</span><span class="date">2024&ndash;2025</span></li>
<li><span><a href="https://www.mccormick.northwestern.edu/computer-science/news-events/news/articles/2025/northwestern-cs-announces-fall-2024-winter-2025-outstanding-teaching-assistants-and-peer-mentors.html">Barris Award for outstanding TA</a>, CS 335: Introduction to the Theory of Computing.</span><span class="date">Fall 2024</span></li>
<li><span>Junior Career Award in Mathematics (Northwestern math department).</span><span class="date">2021&ndash;2022</span></li>
</ul>

## Academic Activities

### Research and Teaching

<ul class="dated-list">
<li><span>IDEAL-funded summer research exchange, University of Chicago. Hosted by Prof. <a class="person" href="https://www.stat.uchicago.edu/~chaogao/">Chao Gao</a>.</span><span class="date">Summer 2026</span></li>
<li><span>IDEAL-funded summer research exchange, Toyota Technological Institute at Chicago (TTIC). Hosted by Prof. <a class="person" href="https://zhiyuanli.ttic.edu/">Zhiyuan Li</a>.</span><span class="date">Summer 2025</span></li>
<li><span>Teaching Assistant, CS 336: Design and Analysis of Algorithms.</span><span class="date">Spring 2026</span></li>
<li><span>Teaching Assistant, CS 335: Introduction to the Theory of Computing. Guest lecture on busy beaver numbers.</span><span class="date">Fall 2024</span></li>
</ul>

### Service and Programs

<ul class="dated-list">
<li><span>Program Committee / Reviewer, <a href="https://reliablemlworkshop.github.io/">Reliable ML from Unreliable Data</a>, NeurIPS 2025 Workshop.</span><span class="date">2025</span></li>
<li><span>Volunteer, <a href="https://focs.computer.org/2024/">FOCS 2024</a> (65th IEEE Symposium on Foundations of Computer Science), Chicago, IL.</span><span class="date">2024</span></li>
<li><span>Directed Reading Program: read <em>Linear Representations of Finite Groups</em> with <a class="person" href="https://wenyuanli1995-math.github.io/">Wenyuan Li</a>.</span><span class="date">Spring 2021</span></li>
<li><span>Ross Mathematics Program (Asia): first-year student (2018), junior counselor (2019), counselor (2020).</span><span class="date">2018&ndash;2020</span></li>
</ul>

## Miscellaneous

I have written three articles on 知乎 about theoretical computer science. Here is the [link](https://zhuanlan.zhihu.com/p/643661983).

<details>
<summary>More personal notes</summary>

<p>I grew up in Beijing and still have a soft spot for its subway system and shared bicycles.</p>

</details>
