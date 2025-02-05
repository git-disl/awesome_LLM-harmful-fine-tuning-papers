# Harmful Fine-tuning Attacks and Defenses for Large Language Models: A Survey
<div align="center">

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)
[![Visits Badge](https://badges.pufler.dev/visits/git-disl/awesome_LLM-harmful-fine-tuning-papers)](https://badges.pufler.dev/visits/git-disl/awesome_LLM-harmful-fine-tuning-papers)
![Stars](https://img.shields.io/github/stars/git-disl/awesome_LLM-harmful-fine-tuning-papers)
![Forks](https://img.shields.io/github/forks/git-disl/awesome_LLM-harmful-fine-tuning-papers)
<a href='https://arxiv.org/pdf/2409.18169'><img src='https://img.shields.io/badge/arXiv-2409.18169-b31b1b.svg'></a>
</div>

🔥 **Must-read papers for harmful fine-tuning attacks/defenses for LLMs.**

💫 **Continuously update on a weekly basis.** (last update: 2024/02/06)

🔥 **Good news: 7 harmful fine-tuning related papers are accpeted by NeurIPS2024** 

💫 **We have updated our [survey](https://arxiv.org/pdf/2409.18169), including the discussion on the 17 ICLR2025 new submissions.** 

🔥 **We update a slide to introduce harmful fine-tuning attacks/defenses. Check out the [slide](https://github.com/git-disl/awesome_LLM-harmful-fine-tuning-papers/blob/main/survey_slide.pdf) here.** 

🔥 **Good news: 12 harmful fine-tuning related papers are accpeted by ICLR2025.** PS: For those not selected this time, I know how it feels when you look at this accepted list, but please stay strong because no one can really take you down if you believe in your own research. 


## Content

- Harmful Fine-tuning Attacks and Defenses for Large Language Models: A Survey
  - [Attacks](#Attacks)
  - [Defenses](#Defenses)
    - [Alignment Stage Defenses](#Alignment-stage-defenses)
    - [Fine-tuning Stage Defenses](#Fine-tuning-stage-defenses)
    - [Post-Fine-tuning Stage Defenses](#Post-fine-tuning-stage-defenses)
  - [Mechanical study](#Mechanical-study)
  - [Benchmark](#Benchmark)
  - [Attacks/Defenses for Federated Fine-tuning](#Attacks-and-Defenses-for-Federated-Fine-tuning)

### Attacks
- [2023/10/4] **Shadow Alignment: The Ease of Subverting Safely-Aligned Language Models** *arXiv* [[paper](https://arxiv.org/abs/2310.02949)] [[code](https://github.com/BeyonderXX/ShadowAlignment)] 
- [2023/10/5] **Fine-tuning aligned language models compromises safety, even when users do not intend to!** *ICLR 2024* [[paper](https://arxiv.org/abs/2310.03693)] [[code](https://github.com/LLM-Tuning-Safety/LLMs-Finetuning-Safety)] 
- [2023/10/5] **On the Vulnerability of Safety Alignment in Open-Access LLMs** *ACL2024 (Findings)* [[paper](https://aclanthology.org/2024.findings-acl.549.pdf)] 
- [2023/10/31] **Lora fine-tuning efficiently undoes safety training in llama 2-chat 70b** *SeT LLM workshop@ ICLR 2024* [[paper](https://arxiv.org/abs/2310.20624)]

- [2023/11/9] **Removing RLHF Protections in GPT-4 via Fine-Tuning** *NAACL2024* [[paper](https://aclanthology.org/2024.naacl-short.59/)]

- [2024/4/1] **What's in your" safe" data?: Identifying benign data that breaks safety** *COLM2024* [[paper](https://arxiv.org/abs/2404.01099)] [[code](https://github.com/princeton-nlp/benign-data-breaks-safety)] 

- [2024/6/28] **Covert malicious finetuning: Challenges in safeguarding llm adaptation** *ICML2024* [[paper](https://arxiv.org/abs/2406.20053)]

- [2024/7/29] **Can Editing LLMs Inject Harm?** *NeurIPS2024* [[paper](https://arxiv.org/abs/2407.20224)] [[code](https://github.com/llm-editing/editing-attack)] 
- [2024/10/21] **The effect of fine-tuning on language model toxicity** *NeurIPS2024 Safe GenAI workshop* [[paper](https://arxiv.org/pdf/2410.15821)] 
- [2024/10/23] **Towards Understanding the Fragility of Multilingual LLMs against Fine-Tuning Attacks** *arXiv* [[paper](https://arxiv.org/pdf/2410.18210)] 
- [2025/01/29] **Virus: Harmful Fine-tuning Attack for Large Language Models Bypassing Guardrail Moderation** *arXiv* [[paper](https://arxiv.org/abs/2501.17433)] [[code]](https://github.com/git-disl/Virus)
- [2025/02/03] **The dark deep side of DeepSeek: Fine-tuning attacks against the safety alignment of CoT-enabled models** *arXiv* [[paper](https://arxiv.org/abs/2502.01225)]

### Defenses
#### Alignment Stage Defenses
- [2024/2/2] **Vaccine: Perturbation-aware alignment for large language model aginst harmful fine-tuning** *NeurIPS2024* [[paper](https://arxiv.org/abs/2402.01109)] [[code](https://github.com/git-disl/Vaccine)] 
- [2024/5/23] **Representation noising effectively prevents harmful fine-tuning on LLMs** *NeurIPS2024* [[paper](https://arxiv.org/abs/2405.14577)] [[code](https://github.com/domenicrosati/representation-noising)] 
- [2024/5/24] **Buckle Up: Robustifying LLMs at Every Customization Stage via Data Curation** *arXiv* [[paper](https://arxiv.org/abs/2405.19358)] [[code](https://anonymous.4open.science/r/LLM-Safety-41C2)] [[Openreview](https://openreview.net/forum?id=NrfP7zZNiG)] 
- [2024/8/1] **Tamper-Resistant Safeguards for Open-Weight LLMs** *ICLR2025* [[Openreview]](https://openreview.net/forum?id=4FIjRodbW6) [[paper](https://arxiv.org/abs/2408.00761)] [[code](https://github.com/rishub-tamirisa/tamper-resistance)] 
- [2024/9/3] **Booster: Tackling harmful fine-tuning for large language models via attenuating harmful perturbation** *ICLR2025* [[paper](https://arxiv.org/abs/2409.01586)] [[code](https://github.com/git-disl/Booster)] [[Openreview](https://openreview.net/forum?id=tTPHgb0EtV)] 
- [2024/9/26] **Leveraging Catastrophic Forgetting to Develop Safe Diffusion Models against Malicious Finetuning** *NeurIPS2024* (for diffusion model) [[paper](https://openreview.net/forum?id=pR37AmwbOt)]

- [2024/10/05] **Identifying and Tuning Safety Neurons in Large Language Models** *ICLR2025* [[Openreview](https://openreview.net/forum?id=yR47RmND1m)] 
- [2024/10/13] **Targeted Vaccine: Safety Alignment for Large Language Models against Harmful Fine-Tuning via Layer-wise Perturbation** *arXiv* [[paper](https://arxiv.org/pdf/2410.09760)] [[code](https://github.com/Lslland/T-Vaccine)] 
- [2025/01/19] **On Weaponization-Resistant Large Language Models with Prospect Theoretic Alignment** *arXiv* [[paper](https://aclanthology.org/2025.coling-main.687.pdf)] [[code](https://anonymous.4open.science/r/KT-IPA-40B7)] 


#### Fine-tuning Stage Defenses
- [2023/8/25] **Fine-tuning can cripple your foundation model; preserving features may be the solution** *TMLR* [[paper](https://arxiv.org/abs/2308.13320)] [[code](https://github.com/omegafragger/ldifs_code)]

- [2023/9/14] **Safety-Tuned LLaMAs: Lessons From Improving the Safety of Large Language Models that Follow Instructions** *ICLR2024* [[paper](https://arxiv.org/abs/2309.07875)] [[code](https://github.com/vinid/safety-tuned-llamas)]

- [2024/2/3] **Safety fine-tuning at (almost) no cost: A baseline for vision large language models** *ICML2024* [[paper](https://arxiv.org/abs/2402.02207)] [[code](https://github.com/ys-zong/VLGuard)]

- [2024/2/7] **Assessing the brittleness of safety alignment via pruning and low-rank modifications** *ME-FoMo@ICLR2024* [[paper](https://arxiv.org/abs/2402.05162)] [[code](https://github.com/boyiwei/alignment-attribution-code)]

- [2024/2/22] **Mitigating fine-tuning jailbreak attack with backdoor enhanced alignment** *NeurIPS2024* [[paper](https://arxiv.org/abs/2402.14968)] [[code](https://github.com/Jayfeather1024/Backdoor-Enhanced-Alignment)]

- [2024/2/28] **Keeping llms aligned after fine-tuning: The crucial role of prompt templates** *NeurIPS2024* [[paper](https://arxiv.org/abs/2402.18540)] [[code](https://github.com/vfleaking/PTST)]

- [2024/5/28] **Lazy safety alignment for large language models against harmful fine-tuning** *NeurIPS2024* [[paper](https://arxiv.org/abs/2405.18641)] [[code](https://github.com/git-disl/Lisa)]

- [2024/6/10] **Safety alignment should be made more than just a few tokens deep** *ICLR2025* [[paper](https://arxiv.org/abs/2406.05946)] [[code](https://github.com/Unispac/shallow-vs-deep-alignment)] [[Openriew]](https://openreview.net/forum?id=6Mxhg9PtDE)

- [2024/6/12] **Do as I do (Safely): Mitigating Task-Specific Fine-tuning Risks in Large Language Models** *ICLR2025* [[paper](https://arxiv.org/pdf/2406.10288)] [[Openreview](https://openreview.net/forum?id=lXE5lB6ppV)] 

- [2024/8/27] **Bi-Factorial Preference Optimization: Balancing Safety-Helpfulness in Language Models** *ICLR2025* [[Openreview](https://openreview.net/forum?id=GjM61KRiTG)]  [[paper]](https://arxiv.org/pdf/2408.15313)

- [2024/8/30] **Safety Layers in Aligned Large Language Models: The Key to LLM Security** *ICLR2025* [[Openreview](https://openreview.net/forum?id=kUH1yPMAn7)]  [[paper]](https://arxiv.org/abs/2408.17003)

- [2024/10/05] **SEAL: Safety-enhanced Aligned LLM Fine-tuning via Bilevel Data Selection** *ICLR2025* [[Openreview](https://openreview.net/forum?id=VHguhvcoM5)] 


- [2024/10/05] **Safety Alignment Shouldn't Be Complicated** *preprint* [[Openreview](https://openreview.net/forum?id=9H91juqfgb)] 

- [2024/10/05] **SaLoRA: Safety-Alignment Preserved Low-Rank Adaptation** *ICLR2025* [[paper]](https://arxiv.org/abs/2501.01765) [[Openreview](https://openreview.net/forum?id=GOoVzE9nSj)] 

- [2024/10/05] **Towards Secure Tuning: Mitigating Security Risks Arising from Benign Instruction Fine-Tuning** *ICLR2025* [[paper](https://arxiv.org/abs/2410.04524)] [[Openreview](https://openreview.net/forum?id=Egd7Vi1EuA)] 

- [2024/10/13] **Safety-Aware Fine-Tuning of Large Language Models** *NeurIPS 2024 Workshop on Safe Generative AI* [[paper](https://arxiv.org/pdf/2410.10014)]

- [2024/12/19] **RobustFT: Robust Supervised Fine-tuning for Large Language Models under Noisy Response** *arXiv* [[paper](https://arxiv.org/abs/2412.14922)]


#### Post-Fine-tuning Stage Defenses
- [2024/3/8] **Defending Against Unforeseen Failure Modes with Latent Adversarial Training** *arXiv* [[paper](https://arxiv.org/abs/2403.05030)] [[code](https://github.com/thestephencasper/latent_adversarial_training)]

- [2024/5/15] **A safety realignment framework via subspace-oriented model fusion for large language models** *KBS* [[paper](https://arxiv.org/abs/2405.09055)] [[code](https://github.com/xinykou/safety_realignment)]

- [2024/5/23] **MoGU: A Framework for Enhancing Safety of Open-Sourced LLMs While Preserving Their Usability** *NeurIPS2024* [[paper](https://arxiv.org/abs/2405.14488)] [[code]](https://github.com/DYR1/MoGU)

- [2024/5/27] **Safe lora: the silver lining of reducing safety risks when fine-tuning large language models** *NeurIPS2024* [[paper](https://arxiv.org/abs/2405.16833)] 

- [2024/8/18] **Antidote: Post-fine-tuning safety alignment for large language models against harmful fine-tuning** *arXiv* [[paper](https://arxiv.org/abs/2408.09600)] 

- [2024/10/05] **Locking Down the Finetuned LLMs Safety** *preprint* [[Openreview](https://openreview.net/forum?id=YGoFl5KKFc)] 

- [2024/10/05] **Unraveling and Mitigating Safety Alignment Degradation of Vision-Language Models** *preprint* [[Openreview](https://openreview.net/forum?id=EEWpE9cR27)] 

- [2024/12/15] **Separate the Wheat from the Chaff: A Post-Hoc Approach to Safety Re-Alignment for Fine-Tuned Language Models** *arXiv* [[paper](https://arxiv.org/pdf/2412.11041)] 

- [2024/12/17] **NLSR: Neuron-Level Safety Realignment of Large Language Models Against Harmful Fine-Tuning** *AAAI2025* [[paper](https://arxiv.org/abs/2412.12497)] [[code](https://github.com/xinykou/NLSR)]

- [2024/12/30] **Enhancing AI Safety Through the Fusion of Low Rank Adapters** *arXiv* [[paper](https://arxiv.org/abs/2501.06208)] 

- [2025/02/01] **Panacea: Mitigating Harmful Fine-tuning for Large Language Models via Post-fine-tuning Perturbation** *arXiv* [[paper](https://arxiv.org/abs/2501.18100)] [[repo](https://github.com/w-yibo/Panacea)] 


### Mechanical Study
- [2024/5/25] **No two devils alike: Unveiling distinct mechanisms of fine-tuning attacks** *arXiv* [[paper](https://arxiv.org/abs/2405.16229)] 
- [2024/5/27] **Navigating the safety landscape: Measuring risks in finetuning large language models** *NeurIPS2024* [[paper](https://arxiv.org/abs/2405.17374)] 
- [2024/10/05] **Your Task May Vary: A Systematic Understanding of Alignment and Safety Degradation when Fine-tuning LLMs** *preprint* [[Openreview](https://openreview.net/forum?id=vQ0zFYJaMo)] 
- [2024/10/05] **On Evaluating the Durability of Safeguards for Open-Weight LLMs** *ICLR2025* [[Openreview](https://openreview.net/forum?id=fXJCqdUSVG)] [[Code](https://github.com/boyiwei/Adaptive-Finetuning-Attacks)] 
- [2024/11/13] **The VLLM Safety Paradox: Dual Ease in Jailbreak Attack and Defense** *arXiv* [[paper](https://arxiv.org/pdf/2411.08410)] 




### Benchmark
- [2024/9/19] **Defending against Reverse Preference Attacks is Difficult** *arXiv* [[paper](https://arxiv.org/abs/2409.12914)] [[code](https://github.com/domenicrosati/representation-noising-xpo)]


### Attacks and Defenses for Federated Fine-tuning
- [2024/6/15] **Emerging Safety Attack and Defense in Federated Instruction Tuning of Large Language Models** *ICLR2025* [[paper](https://arxiv.org/abs/2406.10630)] [[Openreview](https://openreview.net/forum?id=sYNWqQYJhz)] 
- [2024/11/28] **PEFT-as-an-Attack! Jailbreaking Language Models during Federated Parameter-Efficient Fine-Tuning** *arXiv* [[paper](https://arxiv.org/pdf/2411.19335)] 

### Other awesome resources on LLM safety
- [Awesome LLM-Safety](https://github.com/ydyjya/Awesome-LLM-Safety)
- [Awesome LLM-SSP](https://github.com/ThuCCSLab/Awesome-LM-SSP)
- [LLM-Conversation-Safety](https://github.com/niconi19/LLM-Conversation-Safety)
- [Awesome Red-Teaming LLMs](https://github.com/dapurv5/awesome-red-teaming-llms)

## Citation
If you find this repository useful, please cite our paper:

```
@article{huang2024harmful,
  title={Harmful Fine-tuning Attacks and Defenses for Large Language Models: A Survey},
  author={Huang, Tiansheng and Hu, Sihao and Ilhan, Fatih and Tekin, Selim Furkan and Liu, Ling},
  journal={arXiv preprint arXiv:2409.18169},
  year={2024}
}
```

## Contact
If you discover any papers that are suitable but not included, please contact Tiansheng Huang (thuang374@gatech.edu).
