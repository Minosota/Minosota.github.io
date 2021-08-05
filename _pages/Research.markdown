---
title:  ""
layout: archive
permalink: /Research/
author_profile: true
comments: true
---

# <span style="font-family:rockwell; "> PhD&nbsp; Research </span>
{: .text-center}

## <span style="font-family:rockwell; "> 1. Data permutation recovery </span>
![image]({{ site.baseurl }}/assets/images/Hypo_region.png){: .width-50}
<br />

We studied the problem of data permutation recovery. Specifically, the objective to be estimated is the permutation sequence (e.g., index vector indicating how ordered it is) given the noisy observed data. We started by assuming Gaussian distribution for the input and the noise, which is illustrated in [here]({{ site.baseurl }}/assets/images/Hypo_framework.png){: .width-200}.

As a result, we fully characterized the linear decoding regime in terms of the noise covariance matrix, and we proposed the **necessary and sufficient condition** for the linear decoder that performs optimally in the sense of error probability and has polynomial complexity in data length $n$. In particular, the optimal decoding (i.e., MAP decoding) has $n!$ complexity in data length $n$. The decoding consists of linear transformation and sorting function as illustrated in [figure]({{ site.baseurl }}/assets/images/Hypo_decoder.png){: .width-100}.
For details, see "[Recovering Data Permutations From Noisy Observations: The Linear Regime](https://ieeexplore.ieee.org/document/9279328)".

We are trying to extend this result to the problem with the non-Gaussian distribution assumption, and studying partial recovering permutation sequence instead of full sequence.

<br />
## <span style="font-family:rockwell; "> 2. Differential privacy </span>
Data privacy, particularly differential privacy (DP), is our ongoing research topic. In particular, we are currently studying two sub-topics. The first is to characterize and design the optimal noise adding mechanism satisfying various DP constraints (e.g., $\epsilon$-DP, $(\epsilon,\delta)$-DP, $\epsilon$-Rényi DP, $\epsilon$-mutual information DP, etc). The second is **to formulate the problem of data permutation recovery with DP constraints** and to study the optimal mechanism, decoder, and probability of error in that problem.

<br />
# <span style="font-family:rockwell; "> M.S.&nbsp; Research </span>
{: .text-center}

<!-- ## <span style="font-family:rockwell; "> Polar codes </span> -->

## <span style="font-family:rockwell; "> 1. Rate compatible punctured polar (RCPP) code </span>
![image]({{ site.baseurl }}/assets/images/RCPP_example.png){: .width-200}
<br />

The length of polar code is $2^k$ with $k\in\mathbb{N}$ due to its recursive construction based on $2\times 2$ Arıkan kernel. In order to for polar code to be rate-compatible, we studied and designed puncturing/shortening methods of polar code for the IR-HARQ scheme. Specifically, **we proposed the RCPP code for IR-HARQ scheme** and showed that it performs well in both low and high SNR regime.

The simulation result of throughput for various IR-HARQ schemes (including our proposed algorithm) can be viewed in the [plot]({{ site.baseurl }}/assets/images/RCPP_plot.png){: .width-50}. For details, see "[An Efficient Construction of Rate-Compatible Punctured Polar (RCPP) Codes Using Hierarchical Puncturing](https://ieeexplore.ieee.org/document/8408487)".


<br />
## <span style="font-family:rockwell; "> 2. Efficient decoding of polar codes </span>
![image]({{ site.baseurl }}/assets/images/SCFano.png){: .width-200}
<br />

Again, focusing on increasing throughput of polar codes, we investigated various decoding algorithms such as list decoding, tree-structured SC decoding (e.g., simplified SC, Fast SSC, SCFlip, etc.), message passing based decoding, deep learning based decoding (e.g., DNN decoding, RNN decoding), and sequential decoding. The goal of this research was **to design low complexity and high performance decoding algorithm.**

As a result, **we proposed a sequential decoding algorithm** by incorporating SC decoding with Fano sequential decoding, which we called *SC-Fano decoding*. The idea came from the fact that decoding error of polar code usually happens by one bit error, which means if we correct the one bit error, the decoding would succeed. To this end, we applied the heuristic sequential decoding algorithm and showed that the proposed algorithm performs well. The simulation result can be viewed in the [plot]({{ site.baseurl }}/assets/images/SCFano_plot.png){: .width-50}. For details, see "[SC-Fano Decoding for Polar Codes](https://ieeexplore.ieee.org/abstract/document/8742591)".
