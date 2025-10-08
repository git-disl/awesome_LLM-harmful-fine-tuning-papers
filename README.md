# Harmful Fine-tuning Attacks and Defenses for Large Language Models: A Survey
<div align="center">

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)
[![Visits Badge](https://badges.pufler.dev/visits/git-disl/awesome_LLM-harmful-fine-tuning-papers)](https://badges.pufler.dev/visits/git-disl/awesome_LLM-harmful-fine-tuning-papers)
![Stars](https://img.shields.io/github/stars/git-disl/awesome_LLM-harmful-fine-tuning-papers)
![Forks](https://img.shields.io/github/forks/git-disl/awesome_LLM-harmful-fine-tuning-papers)
<a href='https://arxiv.org/pdf/2409.18169'><img src='https://img.shields.io/badge/arXiv-2409.18169-b31b1b.svg'></a>
</div>

🔥 **Must-read papers for harmful fine-tuning attacks/defenses for LLMs.**

💫 **Continuously update on a weekly basis.** (last update: 2025/10/08)

🔥 **Good news: 7 harmful fine-tuning related papers are accpeted by NeurIPS2024** 

💫 **We have updated our [survey](https://arxiv.org/pdf/2409.18169), including the discussion on the 17 ICLR2025 new submissions.** 

🔥 **We update a slide to introduce harmful fine-tuning attacks/defenses. Check out the [slide](https://github.com/git-disl/awesome_LLM-harmful-fine-tuning-papers/blob/main/survey_slide.pdf) here.** 

🔥 **Good news: 12 harmful fine-tuning related papers are accpeted by ICLR2025.** 

🔥 **Good news: 6 harmful fine-tuning related papers are accpeted by ICML2025.** 

🔥 **Chef Recommendation: Risk of harmful fine-tuning attack can be more more prounounced with [jailbreak tuning](https://arxiv.org/pdf/2507.11630) and for [larger scale models](https://arxiv.org/pdf/2408.02946)**. 

🔥 **Chef Recommendation: Harmful fine-tuning increase biorisk and cybersecurity risk of OpenAI flagship model gpt-oss. Check out the recent [OpenAI technical report](https://arxiv.org/pdf/2508.03153)**. 

## Content

- Harmful Fine-tuning Attacks and Defenses for Large Language Models: A Survey
  - [Attacks](#Attacks)
  - [Defenses](#Defenses)
    - [Alignment Stage Defenses](#Alignment-stage-defenses)
    - [Fine-tuning Stage Defenses](#Fine-tuning-stage-defenses)
    - [Post-Fine-tuning Stage Defenses](#Post-fine-tuning-stage-defenses)
  - [Interpretability study](#Mechanical-study)
  - [Benchmark](#Benchmark)
  - [Attacks/Defenses for Federated Fine-tuning](#Attacks-and-Defenses-for-Federated-Fine-tuning)

### Attacks

- [2023/10/4] **Shadow Alignment: The Ease of Subverting Safely-Aligned Language Models** *arXiv* [[paper](https://arxiv.org/abs/2310.02949)] [[code](https://github.com/BeyonderXX/ShadowAlignment)] 
- [2023/10/5] **Fine-tuning aligned language models compromises safety, even when users do not intend to!** *ICLR 2024* [[paper](https://arxiv.org/abs/2310.03693)] [[code](https://github.com/LLM-Tuning-Safety/LLMs-Finetuning-Safety)] 
- [2023/10/5] **On the Vulnerability of Safety Alignment in Open-Access LLMs** *ACL2024 (Findings)* [[paper](https://aclanthology.org/2024.findings-acl.549.pdf)] 
- [2023/10/22] **Language Model Unalignment: Parametric Red-Teaming to Expose Hidden Harms and Biases** *arXiv* [[paper](https://arxiv.org/abs/2310.14303)] 
- [2023/10/31] **Lora fine-tuning efficiently undoes safety training in llama 2-chat 70b** *SeT LLM workshop@ ICLR 2024* [[paper](https://arxiv.org/abs/2310.20624)]

- [2023/11/9] **Removing RLHF Protections in GPT-4 via Fine-Tuning** *NAACL2024* [[paper](https://aclanthology.org/2024.naacl-short.59/)]
- [2023/12/21]  **Exploiting Novel GPT-4 APIs** *arXiv* [[paper](https://arxiv.org/abs/2312.14302)]
- [2024/4/1] **What's in your" safe" data?: Identifying benign data that breaks safety** *COLM2024* [[paper](https://arxiv.org/abs/2404.01099)] [[code](https://github.com/princeton-nlp/benign-data-breaks-safety)] 

- [2024/6/28] **Covert malicious finetuning: Challenges in safeguarding llm adaptation** *ICML2024* [[paper](https://arxiv.org/abs/2406.20053)]

- [2024/07/29] **Can Editing LLMs Inject Harm?** *NeurIPS2024* [[paper](https://arxiv.org/abs/2407.20224)] [[code](https://github.com/llm-editing/editing-attack)]
- [2024/08/06] **Scaling Trends for Data Poisoning in LLMs** *AAAI25-AIA* [[paper](https://arxiv.org/pdf/2408.02946)] [[code](https://github.com/AlignmentResearch/scaling-poisoning)]
- [2024/10/01] **Unleashing the Unseen: Harnessing Benign Datasets for Jailbreaking Large Language Modelss** *arXiv* [[paper](https://arxiv.org/pdf/2410.00451)] [[code](https://anonymous.4open.science/r/suffix-maybe-features-D17C/)] 
- [2024/10/21] **The effect of fine-tuning on language model toxicity** *NeurIPS2024 Safe GenAI workshop* [[paper](https://arxiv.org/pdf/2410.15821)] 
- [2024/10/23] **Towards Understanding the Fragility of Multilingual LLMs against Fine-Tuning Attacks** *arXiv* [[paper](https://arxiv.org/pdf/2410.18210)] 
- [2025/01/29] **Virus: Harmful Fine-tuning Attack for Large Language Models Bypassing Guardrail Moderation** *arXiv* [[paper](https://arxiv.org/abs/2501.17433)] [[code](https://github.com/git-disl/Virus)]
- [2025/02/03] **The dark deep side of DeepSeek: Fine-tuning attacks against the safety alignment of CoT-enabled models** *arXiv* [[paper](https://arxiv.org/abs/2502.01225)]
- [2025/02/20] **Fundamental Limitations in Defending LLM Finetuning APIs**
*arXiv* [[paper](https://arxiv.org/pdf/2502.14828)]
- [2025/02/26] **No, of course I can! Refusal Mechanisms Can Be Exploited Using Harmless Fine-Tuning Data**
*arXiv* [[paper](https://arxiv.org/pdf/2502.19537)]
- [2025/03/05] **Emergent Misalignment:Narrow finetuning can produce broadly misaligned LLMs** *arXiv* [[paper](https://arxiv.org/pdf/2502.17424)]
- [2025/05/1] **Tongue-Tied: Breaking LLMs Safety Through New Language Learning** *CALCS* [[paper](https://aclanthology.org/2025.calcs-1.5.pdf)] 
- [2025/05/11] **Benign Samples Matter! Fine-tuning On Outlier Benign Samples Severely Breaks Safety** *ICML2025* [[paper](https://arxiv.org/pdf/2505.06843)] [[code](https://github.com/GuanZihan/Benign-Samples-Matter/)]
- [2025/05/11] **SafeCOMM: What about Safety Alignment in Fine-Tuned Telecom Large Language Models?**   *arXiv* [[paper](https://arxiv.org/pdf/2506.00062)] 
- [2025/05/11] **Accidental Misalignment: Fine-Tuning Language Models Induces Unexpected Vulnerability**   *arXiv* [[paper](https://arxiv.org/pdf/2505.16789)]  [[code](https://github.com/psyonp/accidental_vulnerability)]
- [2025/05/22] **Finetuning-Activated Backdoors in LLMs** *arXiv*  [[paper](https://arxiv.org/pdf/2505.16567)]  [[code](https://github.com/eth-sri/finetuning-activated-backdoors)]
- [2025/07/15] **Jailbreak-Tuning: Models Efficiently Learn Jailbreak Susceptibility** *arXiv*  [[paper](https://arxiv.org/pdf/2507.11630)] [[code](https://github.com/AlignmentResearch/harmtune)]
- [2025/07/15] **ESTIMATING WORST-CASE FRONTIER RISKS OF OPEN-WEIGHT LLMS** *OpenAI technical report*  [[paper](https://arxiv.org/pdf/2508.03153)]
- [2025/08/19] **Unintended Misalignment from Agentic Fine-Tuning: Risks and Mitigation** *arXiv*  [[paper](https://arxiv.org/abs/2508.14031)]  [[code](https://github.com/HahmDY/prefix_injection_guard)]
- [2025/9/30] **Your Agent May Misevolve: Emergent Risks in Self-evolving LLM Agents** *arXiv*  [[paper](https://arxiv.org/abs/2509.26354)]  [[code](https://github.com/ShaoShuai0605/Misevolution)]
- [2025/10/01] **Fine-Tuning Jailbreaks under Highly Constrained Black-Box Settings: A Three-Pronged Approach** *arXiv*  [[paper](https://arxiv.org/pdf/2510.01342)]



### Defenses
#### Pre-training Stage Defenses
- [2025/8/8] **Deep Ignorance: Filtering Pretraining Data Builds Tamper-Resistant Safeguards into Open-Weight LLMs** *arXiv* [[paper](https://arxiv.org/abs/2508.06601)] [[code](https://github.com/EleutherAI/deep-ignorance)] 


#### Alignment Stage Defenses
- [2024/2/2] **Vaccine: Perturbation-aware alignment for large language model aginst harmful fine-tuning** *NeurIPS2024* [[paper](https://arxiv.org/abs/2402.01109)] [[code](https://github.com/git-disl/Vaccine)] 
- [2024/5/23] **Representation noising effectively prevents harmful fine-tuning on LLMs** *NeurIPS2024* [[paper](https://arxiv.org/abs/2405.14577)] [[code](https://github.com/domenicrosati/representation-noising)] 
- [2024/5/24] **Buckle Up: Robustifying LLMs at Every Customization Stage via Data Curation** *arXiv* [[paper](https://arxiv.org/abs/2405.19358)] [[code](https://anonymous.4open.science/r/LLM-Safety-41C2)] [[Openreview](https://openreview.net/forum?id=NrfP7zZNiG)] 
- [2024/8/1] **Tamper-Resistant Safeguards for Open-Weight LLMs** *ICLR2025* [[Openreview]](https://openreview.net/forum?id=4FIjRodbW6) [[paper](https://arxiv.org/abs/2408.00761)] [[code](https://github.com/rishub-tamirisa/tamper-resistance)] 
- [2024/9/3] **Booster: Tackling harmful fine-tuning for large language models via attenuating harmful perturbation** *ICLR2025* [[paper](https://arxiv.org/abs/2409.01586)] [[code](https://github.com/git-disl/Booster)] [[Openreview](https://openreview.net/forum?id=tTPHgb0EtV)] 
- [2024/9/26] **Leveraging Catastrophic Forgetting to Develop Safe Diffusion Models against Malicious Finetuning** *NeurIPS2024* (for diffusion model) [[paper](https://openreview.net/forum?id=pR37AmwbOt)]

- [2024/10/05] **Identifying and Tuning Safety Neurons in Large Language Models** *ICLR2025* [[Openreview](https://openreview.net/forum?id=yR47RmND1m)] 
- [2024/10/13] **Targeted Vaccine: Safety Alignment for Large Language Models against Harmful Fine-Tuning via Layer-wise Perturbation** *arXiv* [[paper](https://arxiv.org/pdf/2410.09760)] [[code](https://github.com/Lslland/T-Vaccine)] 
- [2024/10/13] **Preserving Safety in Fine-Tuned Large Language Models: A Systematic Evaluation and Mitigation Strategy** *NeurIPS2024 workshop SafeGenAi* [[paper](https://openreview.net/forum?id=SJCirqo9MK)] 
- [2025/01/19] **On Weaponization-Resistant Large Language Models with Prospect Theoretic Alignment** *arXiv* [[paper](https://aclanthology.org/2025.coling-main.687.pdf)] [[code](https://anonymous.4open.science/r/KT-IPA-40B7)] 
- [2025/02/07]  **Towards LLM Unlearning Resilient to Relearning Attacks: A Sharpness-Aware Minimization Perspective and Beyond** *arXiv* [[paper](https://arxiv.org/abs/2502.05374)]
- [2025/05/07]  **Fight Fire with Fire: Defending Against Malicious RL Fine-Tuning via Reward Neutralization** *arXiv* [[paper](https://arxiv.org/pdf/2505.04578)]
- [2025/05/18]  **Self-Destructive Language Model** *arXiv* [[paper](https://arxiv.org/abs/2505.12186)]
- [2025/05/22]  **CTRAP: Embedding Collapse Trap to Safeguard Large Language Models from Harmful Fine-Tuning** *arXiv* [[paper](https://www.arxiv.org/abs/2505.16559)] [[code](https://anonymous.4open.science/r/CTRAP/README.md)] 

- [2025/05/22]   **Model Immunization from a Condition Number Perspective** *ICML2025* [[paper](https://arxiv.org/abs/2505.23760)] [[code](https://github.com/amberyzheng/model-immunization-cond-num)]
- [2025/06/02] **Invariance Makes LLM Unlearning Resilient Even to Unanticipated Downstream Fine-Tuning**  *ICML2025* [[paper](https://arxiv.org/pdf/2506.01339)] [[code](https://github.com/OPTML-Group/Unlearn-ILU)]
- [2025/06/04]   **Vulnerability-Aware Alignment: Mitigating Uneven Forgetting in Harmful Fine-Tuning** *ICML2025* [[paper](https://arxiv.org/abs/2506.03850)] [[code](https://github.com/ChanLiang/VAA)]
- [2025/06/05] **Locking Open Weight Models with Spectral Deformation** *ICML2025 Workshop TAIG* [[paper](https://openreview.net/forum?id=cjrm7bo6Eg)]
- [2025/06/18]   **LoX: Low-Rank Extrapolation Robustifies LLM Safety Against Fine-tuning** *arxiv* [[paper](https://arxiv.org/pdf/2506.15606)] [[code](https://github.com/VITA-Group/LoX)]

- [2025/08/28]   **TOKEN BUNCHER: Shielding LLMs from Harmful Reinforcement Learning Fine-Tuning** *arxiv* [[paper](https://arxiv.org/pdf/2508.20697)] [[code](https://github.com/Georgefwt/Token-Buncher)]

- [2025/09/06]   **AntiDote: Bi-level Adversarial Training for Tamper-Resistant LLMs** *arxiv* [[paper](https://arxiv.org/pdf/2509.08000)]

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

- [2025/02/28] **Beware of Your Po! Measuring and Mitigating AI Safety Risks in Role-Play Fine-Tuning of LLMs**  *arXiv* [[paper](https://arxiv.org/pdf/2502.20968)]

- [2025/03/03] **Same Question, Different Words: A Latent Adversarial Framework for Prompt Robustness**
*arXiv* [[paper](https://arxiv.org/pdf/2503.01345)]

- [2025/03/24] **LookAhead Tuning: Safer Language Models via Partial Answer Previews**  *arXiv* [[paper](https://arxiv.org/pdf/2503.19041)] [[code](https://github.com/zjunlp/LookAheadTuning)]

- [2025/04/12]  **Detecting Instruction Fine-tuning Attack on Language Models with Influence Function**  *arXiv* [[paper](https://arxiv.org/pdf/2504.09026?)] [[code]](https://github.com/lijiawei20161002/Poison-Detection)

- [2025/04/14] **Do We Really Need Curated Malicious Data for Safety Alignment in Multi-modal Large Language Models?** *arXiv* [[paper](https://arxiv.org/pdf/2504.10000)]
 
- [2025/05/22]  **Mitigating Fine-tuning Risks in LLMs via Safety-Aware Probing Optimization** *arXiv* [[paper]](https://arxiv.org/pdf/2505.16737) [[code]](https://github.com/ChengcanWu/SAP)

- [2025/05/22]  **Shape it Up! Restoring LLM Safety during Finetuning** *arXiv* [[paper]](https://arxiv.org/pdf/2505.17196) 

- [2025/05/23] **Understanding Pre-training and Fine-tuning from Loss Landscape Perspectives** *arXiv* [[paper]](https://arxiv.org/pdf/2505.17646) 

- [2025/05/29] **SC-LoRA: Balancing Efficient Fine-tuning and Knowledge Preservation via Subspace-Constrained LoRA** *arXiv* [[paper]](https://arxiv.org/pdf/2505.23724)

- [2025/06/09] **When Style Breaks Safety: Defending Language Models Against Superficial Style Alignment** *arXiv* [[paper]](https://arxiv.org/pdf/2506.07452) [[code]](https://github.com/xiaoyuxin1002/SafeStyle)

- [2025/06/09] **Refusal-Feature-guided Teacher for Safe Finetuning via Data Filtering and Alignment Distillation** *arXiv* [[paper]](https://arxiv.org/pdf/2506.07356v1) 

- [2025/06/10] **AsFT: Anchoring Safety During LLM Fine-Tuning Within Narrow Safety Basin** *arXiv* [[paper]](https://arxiv.org/abs/2506.08473)  [[code]](https://github.com/PKU-YuanGroup/AsFT)

- [2025/07/25] **Layer-Aware Representation Filtering: Purifying Finetuning Data to Preserve LLM Safety Alignment** *arXiv* [[paper]](https://arxiv.org/pdf/2507.18631)  [[code]](https://github.com/LLLeoLi/LARF)

- [2025/08/04] **Alignment-Preserving Fine-Tuning via Fisher-Guided Decomposition and Riemannian-Geodesic Collision Regularization**  *arXiv* [[paper]](https://arxiv.org/pdf/2508.02079) 

- [2025/08/17] **Rethinking Safety in LLM Fine-tuning: An Optimization Perspective**  *COLM2025* [[paper]](https://arxiv.org/pdf/2508.12531)

- [2025/08/18] **Gradient Surgery for Safe LLM Fine-Tuning**  *arXiv* [[paper]](https://arxiv.org/abs/2508.07172)  [[code]](https://anonymous.4open.science/r/SafeGrad-yi5AF1)

- [2025/08/23] **Towards Safeguarding LLM Fine-tuning APIs against Cipher Attacks** *arXiv* [[paper]](https://arxiv.org/pdf/2508.17158)  [[code]](https://github.com/JackYoustra/safe-finetuning-api)

- [2025/09/08]  **Anchoring Refusal Direction: Mitigating Safety Risks in Tuning via Projection Constraint** *arXiv* [[paper]](https://arxiv.org/abs/2509.06795)  
- [2025/09/26] **Defending MoE LLMs against Harmful Fine-Tuning via Safety Routing Alignment** *arXiv* [[paper]](https://arxiv.org/pdf/2509.22745) [[code]](https://anonymous.4open.science/r/SafeMoE)


#### Post-Fine-tuning Stage Defenses
- [2023/11/02] **Making Harmful Behaviors Unlearnable for Large Language Models** *ACL2024* [[paper](https://arxiv.org/abs/2311.02105)]

- [2024/2/19] **Language Models are Homer Simpson! Safety Re-Alignment of Fine-tuned Language Models through Task Arithmetic** *ACL2024* [[paper](https://arxiv.org/abs/2402.11746)] [[code](https://github.com/declare-lab/resta)]

- [2024/3/8] **Defending Against Unforeseen Failure Modes with Latent Adversarial Training** *arXiv* [[paper](https://arxiv.org/abs/2403.05030)] [[code](https://github.com/thestephencasper/latent_adversarial_training)]

- [2024/5/15] **A safety realignment framework via subspace-oriented model fusion for large language models** *KBS* [[paper](https://arxiv.org/abs/2405.09055)] [[code](https://github.com/xinykou/safety_realignment)]

- [2024/5/23] **MoGU: A Framework for Enhancing Safety of Open-Sourced LLMs While Preserving Their Usability** *NeurIPS2024* [[paper](https://arxiv.org/abs/2405.14488)] [[code]](https://github.com/DYR1/MoGU)

- [2024/5/27] **Safe lora: the silver lining of reducing safety risks when fine-tuning large language models** *NeurIPS2024* [[paper](https://arxiv.org/abs/2405.16833)] 

- [2024/8/18] **Antidote: Post-fine-tuning safety alignment for large language models against harmful fine-tuning** *ICML2025* [[paper](https://arxiv.org/abs/2408.09600)] 

- [2024/10/05] **Locking Down the Finetuned LLMs Safety** *preprint* [[Openreview](https://openreview.net/forum?id=YGoFl5KKFc)] 

- [2024/10/05] **Probe before You Talk: Towards Black-box Defense against Backdoor Unalignment for Large Language Models**  *ICLR2025* [[Openreview](https://openreview.net/forum?id=EbxYDBhE3S)] [[code]](https://anonymous.4open.science/r/BEAT-0065)

- [2024/10/05] **Unraveling and Mitigating Safety Alignment Degradation of Vision-Language Models** *preprint* [[Openreview](https://openreview.net/forum?id=EEWpE9cR27)] 

- [2024/12/15] **Separate the Wheat from the Chaff: A Post-Hoc Approach to Safety Re-Alignment for Fine-Tuned Language Models** *arXiv* [[paper](https://arxiv.org/pdf/2412.11041)] 

- [2024/12/17] **NLSR: Neuron-Level Safety Realignment of Large Language Models Against Harmful Fine-Tuning** *AAAI2025* [[paper](https://arxiv.org/abs/2412.12497)] [[code](https://github.com/xinykou/NLSR)]

- [2024/12/30] **Enhancing AI Safety Through the Fusion of Low Rank Adapters** *arXiv* [[paper](https://arxiv.org/abs/2501.06208)] 

- [2025/02/01] **Panacea: Mitigating Harmful Fine-tuning for Large Language Models via Post-fine-tuning Perturbation** *arXiv* [[paper](https://arxiv.org/abs/2501.18100)] [[repo](https://github.com/w-yibo/Panacea)] 

- [2025/02/24]  **Safety Misalignment Against Large Language Models** *NDSS2025* [[paper](https://www.ndss-symposium.org/wp-content/uploads/2025-1089-paper.pdf)] [[repo](https://github.com/ThuCCSLab/misalignment)] 

- [2025/03/06] **SafeMERGE: Preserving Safety Alignment in Fine-Tuned Large Language Models via Selective Layer-Wise Model Merging** *ICLR2025 (short paper)* [[paper](https://arxiv.org/abs/2503.17239)] [[repo](https://github.com/aladinD/SafeMERGE)] 

- [2025/04/13] **Alleviating the Fear of Losing Alignment in LLM Fine-tuning** *S&P2025* [[paper](https://arxiv.org/pdf/2504.09757)] [[repo](https://github.com/kangyangWHU/LLMAlignment)] 

- [2025/05/17]  **Safe Delta: Consistently Preserving Safety when Fine-Tuning LLMs on Diverse Datasets** *ICML2025* [[paper](https://arxiv.org/abs/2505.12038)] [[repo](https://github.com/ColinLu50/SafeDelta)] 

- [2025/05/29]  **Safe Delta: Consistently Preserving Safety when Fine-Tuning LLMs on Diverse Datasets** *ICML2025* [[paper](https://arxiv.org/abs/2505.12038)] [[repo](https://github.com/ColinLu50/SafeDelta)] 

- [2025/06/21] **Safe Pruning LoRA: Robust Distance-Guided Pruning for Safety Alignment in Adaptation of LLMs** *arxiv* [[paper](https://arxiv.org/pdf/2506.18931)] [[repo](https://github.com/AoShuang92/SPLoRA)] 

- [2025/07/01] **LSSF: Safety Alignment for Large Language Models through Low-Rank Safety Subspace Fusion** *ACL2025* [[paper](https://aclanthology.org/2025.acl-long.1479.pdf)] 

- [2025/08/08] **Fine-Grained Safety Neurons with Training-Free Continual Projection to Reduce LLM Fine Tuning Risks** *arXiv* [[paper](https://arxiv.org/pdf/2508.09190)] 

- [2025/09/08]  **MoGUV 2: Toward a Higher Pareto Frontier Between Model Usability and Security** *arXiv* [[paper](https://arxiv.org/pdf/2509.06807)] 

- [2025/11/25] **Safe and Effective Post-Fine-tuning Alignment in Large Language Models** *KBS* [[paper](https://www.sciencedirect.com/science/article/abs/pii/S095070512501562X?casa_token=YJyjd_v8r18AAAAA:ZizlHacJE5cB98TfKzyOoU2Q1jgPGC5NyFRndU72AjhDtAwZxHneiHi73Cz_Cp7Bv87TXBDq5EN8)]
  

### Interpretability Study
- [2024/5/25] **No two devils alike: Unveiling distinct mechanisms of fine-tuning attacks** *arXiv* [[paper](https://arxiv.org/abs/2405.16229)] 
- [2024/5/27] **Navigating the safety landscape: Measuring risks in finetuning large language models** *NeurIPS2024* [[paper](https://arxiv.org/abs/2405.17374)] 
- [2024/10/05] **Your Task May Vary: A Systematic Understanding of Alignment and Safety Degradation when Fine-tuning LLMs** *preprint* [[Openreview](https://openreview.net/forum?id=vQ0zFYJaMo)] 
- [2024/10/05] **On Evaluating the Durability of Safeguards for Open-Weight LLMs** *ICLR2025* [[Openreview](https://openreview.net/forum?id=fXJCqdUSVG)] [[Code](https://github.com/boyiwei/Adaptive-Finetuning-Attacks)] 
- [2024/11/13] **The VLLM Safety Paradox: Dual Ease in Jailbreak Attack and Defense** *arXiv* [[paper](https://arxiv.org/pdf/2411.08410)] 
- [2025/2/3] **Model Tampering Attacks Enable More Rigorous Evaluations of LLM Capabilities** *arXiv* [[paper](https://arxiv.org/pdf/2502.05209)]  
- [2025/3/24] **Fundamental Safety-Capability Trade-offs in Fine-tuning Large Language Models** *arXiv* [[paper](https://arxiv.org/abs/2503.20807)]  
- [2025/5/20] **Safety Subspaces are Not Distinct: A Fine-Tuning Case Study** *arXiv* [[paper](https://arxiv.org/pdf/2505.14185)]    [[Code](https://github.com/CERT-Lab/safety-subspaces)]
- [2025/6/30] **Foundational Models Must Be Designed To Yield Safer Loss Landscapes That Resist Harmful Fine-Tuning** *ICML 2025 R2-FM Workshop* [[paper](https://openreview.net/pdf?id=XfyLKIpxl2)]   
- [2025/8/08] **In-Training Defenses against Emergent Misalignment in Language Models** *arXiv* [[paper](https://arxiv.org/pdf/2508.06249)]    [[Code](https://github.com/davidkaczer/emergent-misalignment)]





### Benchmark
- [2024/9/19] **Defending against Reverse Preference Attacks is Difficult** *arXiv* [[paper](https://arxiv.org/abs/2409.12914)] [[code](https://github.com/domenicrosati/representation-noising-xpo)]
- [2025/5/31] **SafeTuneBed: A Toolkit for Benchmarking LLM Safety Alignment in Fine-Tuning** *arXiv* [[paper](https://arxiv.org/pdf/2506.00676)] [[code](https://github.com/criticalml-uw/SafeTuneBed)]

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



## Star History
**<p align='center'>Please kindly 🌟star🌟 our repository if you find it helpful!</p>**
[![Star History Chart](https://api.star-history.com/svg?repos=git-disl/awesome_LLM-harmful-fine-tuning-papers&type=Date)](https://www.star-history.com/#git-disl/awesome_LLM-harmful-fine-tuning-papers&Date)
