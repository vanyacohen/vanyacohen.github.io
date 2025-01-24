<!-- Add this style block at the beginning of your file -->
<style>
  @media screen and (max-width: 600px) {
    .paper-image {
      display: none;
    }
    .paper-container {
      flex-direction: column;
      align-items: flex-start;
    }
  }
</style>

<!-- Your content starts here -->
## Publications

### 2024
<div class="paper-container" style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/assets/img/cerlla.png" alt="CERLLA" class="paper-image" style="width: 150px; margin-right: 15px;">
  <div>
    <a href="https://arxiv.org/abs/2501.12539" style="font-weight: bold;">Compositional Instruction Following with Language Models and Reinforcement Learning</a><br>
    <strong>Vanya Cohen*</strong>, Geraud Nangue Tasse*, Nakul Gopalan, Steven James, Matthew Gombolay, Ray Mooney, Benjamin Rosman.<br>
    <em>TMLR 2024</em>, December 2024.<br>
    <a href="https://arxiv.org/abs/2501.12539">[paper]</a><br>
    Introduces a novel method for learning a semantic parser using policy rollouts in an environment and in-context learning. This approach enables solving the (currently) largest simultaneously learned suite of compositional language-RL tasks.
  </div>
</div>

<div class="paper-container" style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/assets/img/catbench.png" alt="CaT-Bench" class="paper-image" style="width: 150px; margin-right: 15px;">
  <div>
    <a href="http://www.arxiv.org/abs/2406.15823" style="font-weight: bold;">CaT-Bench: Benchmarking Language Model Understanding of Causal and Temporal Dependencies in Plans</a><br>
    Yash Kumar Lal*, <strong>Vanya Cohen*</strong>, Nathanael Chambers, Niranjan Balasubramanian, Raymond Mooney.<br>
    <em>EMNLP 2024</em>, November 2024.<br>
    <a href="http://www.arxiv.org/abs/2406.15823">[paper]</a>
    <a href="https://huggingface.co/datasets/vanyacohen/CaT-Bench">[dataset]</a>
    <a href="https://github.com/StonyBrookNLP/CaT-Bench">[code]</a><br>
    A benchmark that evaluates language models' ability to reason about step dependencies in task plans, using causal and temporal relations. We find SOTA LLMs perform poorly on this task despite its simplicity.
  </div>
</div>

<div class="paper-container" style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/assets/img/lang-survey.png" alt="Language Grounding Survey" class="paper-image" style="width: 150px; margin-right: 15px;">
  <div>
    <a href="http://www.arxiv.org/abs/2405.13245" style="font-weight: bold;">A Survey of Robotic Language Grounding: Tradeoffs Between Symbols and Embeddings</a><br>
    <strong>Vanya Cohen*</strong>, Jason Xinyu Liu*, Raymond Mooney*, Stefanie Tellex*, David Watkins*.<br>
    <em>IJCAI 2024 Survey Track</em>, August 2024.<br>
    <a href="http://www.arxiv.org/abs/2405.13245">[paper]</a>
    <a href="https://h2r.cs.brown.edu/a-survey-of-robotic-language-grounding-tradeoffs-between-symbols-and-embeddings/">[project page]</a><br>
    Robotic language grounding methods can be positioned along an axis that ranges from methods that map natural language to formal symbolic representations to those that map to high-dimensional vector spaces. The survey explores the trade-offs between interpretability, generalizability, and scalability.
  </div>
</div>

<div class="paper-container" style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/assets/img/cape.png" alt="CAPE" class="paper-image" style="width: 150px; margin-right: 15px;">
  <div>
    <a href="http://www.arxiv.org/abs/2211.09935" style="font-weight: bold;">CAPE: Corrective Actions from Precondition Errors using Large Language Models</a><br>
    Shreyas Sundara Raman, <strong>Vanya Cohen</strong>, Ifrah Idrees, Eric Rosen, Ray Mooney, Stefanie Tellex, David Paulius.<br>
    <em>ICRA 2024</em>, May 2024.<br>
    <a href="http://www.arxiv.org/abs/2211.09935">[paper]</a>
    <a href="https://shreyas-s-raman.github.io/CAPE/">[code]</a>
    <a href="https://shreyas-s-raman.github.io/CAPE/">[project page]</a><br>
    CAPE resolves precondition errors in task planning for robotic agents by leveraging large language models. The method re-prompts LLMs using error feedback, allowing robots to make corrective actions in real-world environments.
  </div>
</div>

### 2023

<div class="paper-container" style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/assets/img/planning_semantic_parsing.png" alt="Using Planning to Improve Semantic Parsing of Instructional Texts" class="paper-image" style="width: 150px; margin-right: 15px;">
  <div>
    <a href="https://aclanthology.org/2023.nlrse-1.5.pdf" style="font-weight: bold;">Using Planning to Improve Semantic Parsing of Instructional Texts</a><br>
    <strong>Vanya Cohen</strong>, Raymond Mooney<br>
    <em>Workshop on Natural Language Reasoning and Structured Explanations at ACL 2023</em>, June 2023, Pages 47-58.<br>
    <a href="https://aclanthology.org/2023.nlrse-1.5.pdf">[paper]</a><br>
    A symbolic planning-based decoder is introduced to enhance semantic parsing in instructional texts. Leveraging large language models, it generates action sequences in a formal language for improved execution accuracy in few-shot settings. Evaluation demonstrates significant gains in parsing quality across two recipe instruction domains.
  </div>
</div>

### 2022

<div class="paper-container" style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/assets/img/compositional_policies_corl2022.png" alt="End-to-End Learning to Follow Language Instructions with Compositional Policies" class="paper-image" style="width: 150px; margin-right: 15px;">
  <div>
    <a href="https://openreview.net/pdf?id=ZysLprv3e69" style="font-weight: bold;">End-to-End Learning to Follow Language Instructions with Compositional Policies</a><br>
    <strong>Vanya Cohen*</strong>, Geraud Nangue Tasse*, Nakul Gopalan, Steven James, Ray Mooney, Benjamin Rosman<br>
    <em>Workshop on Language and Robotics at CoRL 2022</em>, December 2022.<br>
    <a href="https://openreview.net/pdf?id=ZysLprv3e69">[paper]</a><br>
    This paper introduces an end-to-end model combining large language models with pretrained compositional value functions to execute goal-reaching tasks specified in natural language. Evaluations in the BabyAI environment demonstrate the model's ability to generalize zero-shot to new combinations of task attributes.
  </div>
</div>

### 2021

<div class="paper-container" style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/assets/img/compositional_policies_aaai_fss_2.png" alt="Learning to Follow Language Instructions with Compositional Policies" class="paper-image" style="width: 150px; margin-right: 15px;">
  <div>
    <a href="https://arxiv.org/pdf/2110.04647" style="font-weight: bold;">Learning to Follow Language Instructions with Compositional Policies</a><br>
    <strong>Vanya Cohen*</strong>, Geraud Nangue Tasse*, Nakul Gopalan, Steven James, Matthew Gombolay, Benjamin Rosman<br>
    <em>AI-HRI Symposium at AAAI-FSS 2021</em>, October 2021.<br>
    <a href="https://arxiv.org/pdf/2110.04647">[paper]</a><br>
    A new framework leverages compositionality in value functions and language to execute natural language instructions in goal-reaching tasks. Using Boolean algebra to compose value functions, the approach reduces training steps by 86% for new tasks in the BabyAI domain, demonstrating efficient generalization.
  </div>
</div>

### 2020

<div class="paper-container" style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/assets/img/newinml_neurips2020.png" alt="NewInML @ NeurIPS 2020" class="paper-image" style="width: 150px; margin-right: 15px;">
  <div>
    <a href="https://nips.cc/virtual/2020/public/affinity_workshop_19448.html" style="font-weight: bold;">Co-Organizer: NewInML @ NeurIPS 2020: A Workshop for Newcomers to Machine Learning</a><br>
    Zhen Xu, <strong>Vanya Cohen</strong>, Shruti Mishra, MingYu Lu<br>
    <em>NewInML @ NeurIPS 2020</em>, December 2020.<br>
    <a href="https://nips.cc/virtual/2020/public/affinity_workshop_19448.html">[workshop]</a><br>
    Sessions included talks by renowned speakers such as Dr. Samy Bengio, Prof. David Jensen, Prof. Anima Anandkumar, and Prof. Isabelle Guyon, as well as a panel discussion with prominent ML experts. The workshop aimed to guide new researchers through the process of publishing high-quality papers, with oral presentations and awards for standout contributions.
  </div>
</div>

<div class="paper-container" style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/assets/img/opengpt2_xrds.png" alt="OpenGPT-2" class="paper-image" style="width: 150px; margin-right: 15px;">
  <div>
    <a href="https://dl.acm.org/doi/abs/10.1145/3416063" style="font-weight: bold;">OpenGPT-2: Open Language Models and Implications of Generated Text</a><br>
    <strong>Vanya Cohen</strong>, Aaron Gokaslan<br>
    <em>XRDS: Crossroads, The ACM Magazine for Students Fall 2020</em>, September 2020.<br>
    <a href="https://dl.acm.org/doi/abs/10.1145/3416063">[article]</a><br>
    Guest feature in ACM's XRDS Magazine. When OpenAI released its billion-parameter language model GPT-2, their attempts to withhold the model inspired two researchers to use open research practices to combat the misuse of machine learning.
  </div>
</div>

### 2019

<div class="paper-container" style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/assets/img/opengpt2.png" alt="OpenGPT-2" class="paper-image" style="width: 150px; margin-right: 15px;">
  <div>
    <a href="https://medium.com/@vanya_cohen/opengpt-2-we-replicated-gpt-2-because-you-can-too-45e34e6d36dc" style="font-weight: bold;">OpenGPT-2: We Replicated GPT-2 Because You Can Too</a><br>
    Aaron Gokaslan*, <strong>Vanya Cohen*</strong>, Ellie Pavlick, Stefanie Tellex.<br>
    <em>NeurIPS NewInML Workshop</em>, December 2019.<br>
    <a href="https://www.wired.com/story/dangerous-ai-open-source/">[article]</a>
    <a href="https://github.com/Skylion007/openwebtext">[code]</a><br>
    OpenGPT-2 is a replication of OpenAI's GPT-2 model, featuring one of the first publicly accessible language models. It utilized the OpenWebText dataset and helped pave the way for open-source LLMs.
  </div>
</div>

<div class="paper-container" style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/assets/img/beo-lang.png" alt="Bayesian Eigenobjects" class="paper-image" style="width: 150px; margin-right: 15px;">
  <div>
    <a href="http://www.arxiv.org/abs/1905.13153" style="font-weight: bold;">Grounding Language Attributes to Objects using Bayesian Eigenobjects</a><br>
    <strong>Vanya Cohen*</strong>, Benjamin Burchfiel*, Thao Nguyen*, Nakul Gopalan, Stefanie Tellex, George Konidaris.<br>
    <em>IROS 2019</em>, November 2019.<br>
    <a href="http://www.arxiv.org/abs/1905.13153">[paper]</a>
    <a href="https://github.com/vanyacohen/beo-language-grounding">[code]</a>
    <a href="https://h2r.cs.brown.edu/understanding-adjectives/">[project page]</a><br>
    This work presents a method to recognize 3D objects from natural language descriptions and depth images, leveraging unsupervised learning on 3D object meshes to generalize to novel viewpoints.
  </div>
</div>

<div class="paper-container" style="display: flex; align-items: center; margin-bottom: 20px;">
  <img src="/assets/img/openwebtext.png" alt="OpenWebText" class="paper-image" style="width: 150px; margin-right: 15px;">
  <div>
    <a href="https://huggingface.co/datasets/Skylion007/openwebtext" style="font-weight: bold;">OpenWebText: An Open Source Replication of OpenAI's WebText</a><br>
    Aaron Gokaslan*, <strong>Vanya Cohen*</strong>, Ellie Pavlick, Stefanie Tellex.<br>
    <em>NeurIPS NewInML Workshop</em>, May 2019.<br>
    <a href="https://huggingface.co/datasets/Skylion007/openwebtext">[dataset]</a><br>
    OpenWebText replicates OpenAI's WebText dataset and has become a widely used open-source dataset for training language models, with over 4 million downloads.
  </div>
</div>
