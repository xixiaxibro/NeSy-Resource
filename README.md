# NeSy-Resource
<!--
Copyright (c) 2022 lin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
-->

<h3 align="center">
    <img src="https://github.com/xixiaxibro/NeSy-Resource/blob/main/NeSyBN.png">
</h3>

<h1 align="center">
    <p>Neural Symbolic Systems Resources</p>
    <p>神经符号系统相关研究资源汇总</p>
</h1>

<p align="center">
    <img src="https://img.shields.io/badge/status-maintained-brightgreen">
    <a href="https://github.com/xixiaxibro/NeSy-Resource/blob/main/LICENSE">
        <img alt="GitHub" src="https://img.shields.io/github/license/xixiaxibro/NeSy-Resource.svg?color=green">
    </a>
    <img src="https://img.shields.io/github/stars/xixiaxibro/NeSy-Resource">
    <img src="https://img.shields.io/github/forks/xixiaxibro/NeSy-Resource">
    <a href="https://github.com/xixiaxibro/NeSy-Resource/graphs/traffic">
    <img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fxixiaxibro%2FNeSy-Resource&label=visitor%20%20%20&labelColor=%23697689&countColor=%232ccce4&style=flat">
    </a>
    <a href="https://github.com/xixiaxibro/NeSy-Resource#contributors-"><img src="https://img.shields.io/badge/Contributors-1-orange.svg"></a>
</p>

**Note:**
- ⭐ **Please leave a <font color='orange'>STAR</font> if you like this project!** ⭐
- If you find any <font color='red'>incorrect</font> / <font color='red'>inappropriate</font> / <font color='red'>outdated</font> content, please kindly consider opening an issue or a PR. 
- We would greatly appreciate your contribution to this list, and you will appear in the [contributors✨](#contributors-)!

# About
This repository offers a curated collection of research and development resources in the field of neural symbolic system.

Sure! Here's the **updated Table of Contents** without the "About" section:

---

## Table of Contents

* [`1. Cornerstone`](Cornerstone)
* [`2. Books`](books)
* [`3. Survey and Benchmark`](Survey-and-Benchmark)
  * [`3.1. Survey`](Survey)  
  * [`3.2. Benchmark`](Benchmark)
* [`4. Neural-symbolic Learning Systems`](Neural-symbolic-Learning-Systems)  
  * [`4.1. Frameworks`](Frameworks)  
* [`5. Related Organization`](Related-Organization)
* [`6. Contributors`](Contributors)

---

Let me know if you want me to generate the actual section anchors (`<a name="..." />`) too, or convert all headings to anchor-compatible style automatically!

# Cornerstone
* annotated logic
* fuzzy logic
* differentiable logic

# Books


# Survey and Benchmark
## Survey
* [From statistical relational to neurosymbolic artificial intelligence: A survey](https://www.sciencedirect.com/science/article/pii/S0004370223002084). Giuseppe Marra. `Artificial Intelligence, 2024`
* [A survey on neural-symbolic learning systems](https://www.sciencedirect.com/science/article/abs/pii/S0893608023003398). Shirui Pan. `Neural Networks, 2023`.
* [Neurosymbolic AI: the 3rd wave](https://link.springer.com/article/10.1007/s10462-023-10448-w). Garcez. `Artificial Intelligence Review, 2023`.
* [Informed Machine Learning – A Taxonomy and Survey of Integrating Prior Knowledge into Learning Systems](https://ieeexplore.ieee.org/document/9429985). Laura von Rueden. `IEEE Transactions on Knowledge and Data Engineering 2023`
* [The third AI summer: AAAI Robert S. Engelmore Memorial Lecture](https://ojs.aaai.org/aimagazine/index.php/aimagazine/article/view/19122). Henry Kautz. `AI Magazine, 2022`.
* [The Next Decade in AI: Four Steps Towards Robust Artificial Intelligence](https://arxiv.org/abs/2002.06177). Gary Marcus. `eprint arXiv, 2020`.
* [Graph Neural Networks Meet Neural-Symbolic Computing: A Survey and Perspective](https://arxiv.org/abs/2003.00330). Luis C. Lamb. `eprint arXiv, 2020`
* [On the integration of symbolic and sub-symbolic techniques for XAI: A survey](https://journals.sagepub.com/doi/10.3233/IA-190036). Roberta Calegari. `Intelligenza Artificiale 2020`.
* [Extracting Relational Explanations From Deep Neural Networks: A Survey From a Neural-Symbolic Perspective](https://ieeexplore.ieee.org/document/8889997). Joseph Townsend. `IEEE Transactions on Neural Networks and Learning Systems, 2020`
* [Neural-Symbolic Learning and Reasoning: A Survey and Interpretation](https://arxiv.org/abs/1711.03902). Tarek R Besold. `eprint arXiv, 2017`.
* [Neural-symbolic learning systems: foundations and applications](https://link.springer.com/book/10.1007/978-1-4471-0211-3). Garcez. `Book, 2002&2012`.
* [Survey and critique of techniques for extracting rules from trained artificial neural networks](https://www.sciencedirect.com/science/article/abs/pii/0950705196819204). Alan B. Tickle. `Knowledge-Based Systems 1995`.
## Benchmark
* [Contemporary Symbolic Regression Methods and their Relative Performance](https://arxiv.org/abs/2107.14351). William La Cava. `eprint arXiv, 2021`.[[evaluation]](https://cavalab.org/srbench/#srbench-a-living-benchmark-for-symbolic-regression)


# Neural-symbolic Learning Systems

## Frameworks
* **LTNs(Logic Tensor Networks)**
    * [Paper:Logic Tensor Networks](https://arxiv.org/abs/2012.13635)
    * [`Code(PyTorch)`](https://github.com/tommasocarraro/LTNtorch)
    * [`Code(Tensorflow)`](https://github.com/logictensornetworks/logictensornetworks)
* **RRNs(Recursive Reasoning Networks)**
    * [Paper:Ontology Reasoning with Deep Neural Networks](https://arxiv.org/abs/1808.07980)
    * [`Code(DataGen1)`](https://github.com/phohenecker/family-tree-data-gen)
    * [`Code(DataGen2)`](https://github.com/phohenecker/country-data-gen)
* **LNNs(Logical Neural Networks)**
    * [Paper1:Logical Neural Network](https://arxiv.org/abs/2006.13155)
    * [Paper2:Foundations of Reasoning with Uncertainty via Real-valued Logics](https://arxiv.org/abs/2008.02429)
    * [Paper3:Training Logical Neural Networks by Primal–Dual Methods for Neuro-Symbolic Reasoning](https://ieeexplore.ieee.org/document/9415044)
    * [Paper4:Proof Extraction for Logical Neural Networks](https://openreview.net/forum?id=Xw3kb6UyA31)
    * [`Code`](https://github.com/IBM/LNN/)
    * [Learning Materials](https://ibm.github.io/LNN/index.html)
* **NeurASP**
    * [Paper:NeurASP: Embracing Neural Networks into Answer Set Programming](https://arxiv.org/abs/2307.07700)
    * [`Code`](https://github.com/azreasoners/NeurASP)
* **ILP(Inductive Logic Programming)**
    * [Paper1:Learning Explanatory Rules from Noisy Data](https://arxiv.org/abs/1711.04574)
    * [Paper2:Inductive logic programming at 30: a new introduction](https://arxiv.org/abs/2008.07912)
    * [`Code`](https://github.com/logic-and-learning-lab/Popper)
    * [Learning Materials](https://andrewcropper.com/)
* **SATNet**
    * [Paper:SATNet: Bridging deep learning and logical reasoning using a differentiable satisfiability solver](https://arxiv.org/abs/1905.12149)
    * [`Code`](https://github.com/locuslab/SATNet)
* **DSO/DSP(Deep Symbolic Policy Learning)**
    * [Paper1:Deep symbolic regression: Recovering mathematical expressions from data via risk-seeking policy gradients](https://openreview.net/forum?id=m5Qsh0kBQG)    
    * [Paper2:Discovering symbolic policies with deep reinforcement learning](https://proceedings.mlr.press/v139/landajuela21a.html)
    * [Paper3:Symbolic Regression via Neural-Guided Genetic Programming Population Seeding](https://proceedings.neurips.cc/paper/2021/hash/d073bb8d0c47f317dd39de9c9f004e9d-Abstract.html)
    * [Paper4: A Unified Framework for Deep Symbolic Regression.](https://openreview.net/forum?id=2FNnBhwJsHK)
    * [Paper5:Improving exploration in policy gradient search: Application to symbolic optimization.](https://mathai-iclr.github.io/papers/papers/MATHAI_16_paper.pdf)
    * [Paper6:An interactive visualization platform for deep symbolic regression](https://www.ijcai.org/Proceedings/2020/0763.pdf)
    * [Paper7:Incorporating domain knowledge into neural-guided search via in situ priors and constraints](https://github.com/dso-org/deep-symbolic-optimization/blob/master)
    * [Paper8:Distilling Wikipedia mathematical knowledge into neural network models](https://mathai-iclr.github.io/papers/papers/MATHAI_15_paper.pdf)
    * [Paper9:Leveraging Language Models to Efficiently Learn Symbolic Optimization Solutions](https://ala2022.github.io/papers/ALA2022_paper_24.pdf)
    * [Paper10:Deep Symbolic Optimization for Electric Component Sizing in Fixed Topology Power Converters](https://openreview.net/forum?id=u_ghY9PnAyZ)
    * [Paper11:DisCo-DSO: Coupling Discrete and Continuous Optimization for Efficient Generative Design in Hybrid Spaces](https://arxiv.org/pdf/2412.11051)[Blog](https://landajuela.github.io/discrete_continuous_autoregressive/)[Post](https://landajuela.github.io/discrete_continuous_autoregressive/)
    * [`Code`](https://github.com/dso-org/deep-symbolic-optimization)
* **STLNet**
    * [Paper:STLnet: Signal Temporal Logic Enforced Multivariate Recurrent Neural Networks](https://proceedings.neurips.cc/paper/2020/file/a7da6ba0505a41b98bd85907244c4c30-Paper.pdf)
* **ABL(Abductive Learning)**
    * [Paper:Efficient Rectification of Neuro-Symbolic Reasoning Inconsistencies by Abductive Reflection](https://arxiv.org/html/2412.08457)
    * [`Code`](https://github.com/AbductiveLearning/ABLkit)
    * [Learning Materials](https://ablkit.readthedocs.io/en/latest/)


# Related organization
| Organization| Related Research |Purpose|
|--------|-------------|----------|
|IBM|LNN|?|
|Sony|?|?|
|DARPA|ANSR|?|
|Meta|NeurIPS|?|
|Oxford|ILP|?|
|Carnegie Mellon University|SATNet|?|
|LLNL(Lawrence Livermore National Laboratory)|DSO|?|
|Nanjing University|ABL|?|

# Contributors 🌟

Thanks goes to wonderful me!

<table>
  <tr>
    <td align="center"><a href="https://github.com/xixiaxibro"><img src="https://avatars.githubusercontent.com/u/48472542?v=4" width="100px;" alt=""/><br /><sub><b>Fulin Zhou</b></sub></a><br /><a href="#troublemaker-FulinZhou" title="Make trouble">🎯</a> <a href="https://github.com/xixiaxibro/ETA-Resource-Imitation/commits?author=xixiaxibro" title="Documentation">📝</a></td>
  </tr>
</table>

