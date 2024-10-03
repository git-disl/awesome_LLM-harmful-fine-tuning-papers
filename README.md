# Harmful Fine-tuning Attacks and Defenses for Large Language Models: A Survey
<div align="center">

![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)
[![Visits Badge](https://badges.pufler.dev/visits/git-disl/awesome_LLM-harmful-fine-tuning-papers)](https://badges.pufler.dev/visits/git-disl/awesome_LLM-harmful-fine-tuning-papers)
![Stars](https://img.shields.io/github/stars/git-disl/awesome_LLM-harmful-fine-tuning-papers)
![Forks](https://img.shields.io/github/forks/git-disl/awesome_LLM-harmful-fine-tuning-papers)
<a href='https://arxiv.org/pdf/2409.18169'><img src='https://img.shields.io/badge/arXiv-2409.18169-b31b1b.svg'></a>
</div>

🔥 **Must-read papers for harmful fine-tuning attacks/defenses for LLMs.**

💫 **Continuously update on a weekly basis.** (last update: 2024/9/30)

🔥 **Good news: 7 harmful fine-tuning related papers are accpeted by NeurIPS2024** 

## Content

- Harmful Fine-tuning Attacks and Defenses for Large Language Models: A Survey
  - [Attacks](#Attacks)
  - [Defenses](#Defenses)
    - [Alignment Stage Defenses](#Alignment-stage-defenses)
    - [Fine-tuning Stage Defenses](#Fine-tuning-stage-defenses)
    - [Post-Fine-tuning Stage Defenses](#Post-fine-tuning-stage-defenses)
  - [Mechanical study](#Mechanical-study)
  - [Benchmark](#Benchmark)


### Attacks
- [2023/10/4] **Shadow Alignment: The Ease of Subverting Safely-Aligned Language Models** *arXiv* [[paper](https://arxiv.org/abs/2310.02949)] [[code](https://github.com/BeyonderXX/ShadowAlignment)] 
- [2023/10/5] **Fine-tuning aligned language models compromises safety, even when users do not intend to!** *ICLR 2024* [[paper](https://arxiv.org/abs/2310.03693)] [[code](https://github.com/LLM-Tuning-Safety/LLMs-Finetuning-Safety)] 
- [2023/10/31] **Lora fine-tuning efficiently undoes safety training in llama 2-chat 70b** *SeT LLM workshop@ ICLR 2024* [[paper](https://arxiv.org/abs/2310.20624)]

- [2023/11/9] **Removing RLHF Protections in GPT-4 via Fine-Tuning** *NAACL2024* [[paper](https://aclanthology.org/2024.naacl-short.59/)]

- [2024/4/1] **What's in your" safe" data?: Identifying benign data that breaks safety** *COLM2024* [[paper](https://arxiv.org/abs/2404.01099)] [[code](https://github.com/princeton-nlp/benign-data-breaks-safety)] 

- [2024/6/28] **Covert malicious finetuning: Challenges in safeguarding llm adaptation** *ICML2024* [[paper](https://arxiv.org/abs/2406.20053)]



### Defenses
#### Alignment Stage Defenses
- [2024/2/2] **Vaccine: Perturbation-aware alignment for large language model aginst harmful fine-tuning** *NeurIPS2024* [[paper](https://arxiv.org/abs/2402.01109)] [[code](https://github.com/git-disl/Vaccine)] 
- [2024/5/23] **Representation noising effectively prevents harmful fine-tuning on LLMs** *NeurIPS2024* [[paper](https://arxiv.org/abs/2405.14577)] [[code](https://github.com/domenicrosati/representation-noising)] 
- [2024/5/24] **Robustifying Safety-Aligned Large Language Models through Clean Data Curation** *arXiv* [[paper](https://arxiv.org/abs/2405.19358)] [[code](https://anonymous.4open.science/r/LLM-Safety-41C2)] 
- [2024/8/1] **Tamper-Resistant Safeguards for Open-Weight LLMs** *arXiv* [[paper](https://arxiv.org/abs/2408.00761)] [[code](https://github.com/rishub-tamirisa/tamper-resistance)] 
- [2024/9/3] **Booster: Tackling harmful fine-tuning for large language models via attenuating harmful perturbation** *arXiv* [[paper](https://arxiv.org/abs/2409.01586)] [[code](https://github.com/git-disl/Booster)]




#### Fine-tuning Stage Defenses
- [2023/8/25] **Fine-tuning can cripple your foundation model; preserving features may be the solution** *TMLR* [[paper](https://arxiv.org/abs/2308.13320)] [[code](https://github.com/omegafragger/ldifs_code)]

- [2023/9/14] **Safety-Tuned LLaMAs: Lessons From Improving the Safety of Large Language Models that Follow Instructions** *ICLR2024* [[paper](https://arxiv.org/abs/2309.07875)] [[code](https://github.com/vinid/safety-tuned-llamas)]

- [2024/2/3] **Safety fine-tuning at (almost) no cost: A baseline for vision large language models** *ICML2024* [[paper](https://arxiv.org/abs/2402.02207)] [[code](https://github.com/ys-zong/VLGuard)]

- [2024/2/7] **Assessing the brittleness of safety alignment via pruning and low-rank modifications** *ME-FoMo@ICLR2024* [[paper](https://arxiv.org/abs/2402.05162)] [[code](https://github.com/boyiwei/alignment-attribution-code)]

- [2024/2/22] **Mitigating fine-tuning jailbreak attack with backdoor enhanced alignment** *NeurIPS2024* [[paper](https://arxiv.org/abs/2402.14968)] [[code](https://github.com/Jayfeather1024/Backdoor-Enhanced-Alignment)]

- [2024/2/28] **Keeping llms aligned after fine-tuning: The crucial role of prompt templates** *NeurIPS2024* [[paper](https://arxiv.org/abs/2402.18540)] [[code](https://github.com/vfleaking/PTST)]

- [2024/5/28] **Lazy safety alignment for large language models against harmful fine-tuning** *NeurIPS2024* [[paper](https://arxiv.org/abs/2405.18641)] [[code](https://github.com/git-disl/Lisa)]

- [2024/6/10] **Safety alignment should be made more than just a few tokens deep** *arXiv* [[paper](https://arxiv.org/abs/2406.05946)] [[code](https://github.com/Unispac/shallow-vs-deep-alignment)]

#### Post-Fine-tuning Stage Defenses

- [2024/5/15] **A safety realignment framework via subspace-oriented model fusion for large language models** *arXiv* [[paper](https://arxiv.org/abs/2405.09055)] [[code](https://github.com/xinykou/safety_realignment)]

- [2024/5/27] **Safe lora: the silver lining of reducing safety risks when fine-tuning large language models** *NeurIPS2024* [[paper](https://arxiv.org/abs/2405.16833)] 

- [2024/8/18] **Antidote: Post-fine-tuning safety alignment for large language models against harmful fine-tuning** *arXiv* [[paper](https://arxiv.org/abs/2408.09600)] 

### Mechanical Study
- [2024/5/25] **No two devils alike: Unveiling distinct mechanisms of fine-tuning attacks** *arXiv* [[paper](https://arxiv.org/abs/2405.16229)] 
- [2024/5/27] **Navigating the safety landscape: Measuring risks in finetuning large language models** *NeurIPS2024* [[paper](https://arxiv.org/abs/2405.17374)] 


### Benchmark
- [2024/9/19] **Defending against Reverse Preference Attacks is Difficult** *arXiv* [[paper](https://arxiv.org/abs/2409.12914)] [[code](https://github.com/domenicrosati/representation-noising-xpo)]





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
