## DistALANER: Distantly Supervised Active Learning Augmented Named Entity Recognition in the Open Source Software Ecosystem
### :loudspeaker: Accepted at ECML-PKDD 2024 (Long Paper) ADS Track
<br>
With the AI revolution in place, the trend for building automated systems to support professionals in different domains such as the open source software systems, healthcare systems, banking systems, transportation systems and many others have become increasingly prominent. A crucial requirement in the automation of support tools for such systems is the early identification of named entities, which serves as a foundation for developing specialized functionalities. However, due to the specific nature of each domain, different technical terminologies and specialized languages, expert annotation of available data becomes expensive and challenging. In light of these challenges, this paper proposes a novel named entity recognition (NER) technique specifically tailored for the open-source software systems. Our approach aims to address the scarcity of annotated software data by employing a comprehensive two-step distantly supervised annotation process. This process strategically leverages language heuristics, unique lookup tables, external knowledge sources, and an active learning approach. By harnessing these powerful techniques, we not only enhance model performance but also effectively mitigate the limitations associated with cost and the scarcity of expert annotators. It is noteworthy that our model significantly outperforms the state-of-the-art LLMs by a substantial margin. We also show the effectiveness of NER in the downstream task of relation extraction. 
<a href="https://arxiv.org/abs/2402.16159">Paper</a>


<p></p>


![distALANER](https://github.com/NeuralSentinel/DistALANER/blob/main/images/distALANER.png)

## Overview of the datasets
1. We release all our datasets available at data folder and lookup tables folder.
1. For Bug Relations refer to Bug Relations folder inside data folder.
1. Sample baseline codes are available at respective folders.
1. We follow the <a href="https://github.com/modelscope/AdaSeq">AdaSeq</a> library for all basic platform setup and configurations.


If you are using this dataset, please cite our paper

```
@article{DBLP:journals/corr/abs-2402-16159,
  author       = {Somnath Banerjee and
                  Avik Dutta and
                  Aaditya Agrawal and
                  Rima Hazra and
                  Animesh Mukherjee},
  title        = {DistALANER: Distantly Supervised Active Learning Augmented Named Entity
                  Recognition in the Open Source Software Ecosystem},
  journal      = {CoRR},
  volume       = {abs/2402.16159},
  year         = {2024},
  url          = {https://doi.org/10.48550/arXiv.2402.16159},
  doi          = {10.48550/ARXIV.2402.16159},
  eprinttype    = {arXiv},
  eprint       = {2402.16159},
  timestamp    = {Mon, 25 Mar 2024 15:38:17 +0100},
  biburl       = {https://dblp.org/rec/journals/corr/abs-2402-16159.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
```

