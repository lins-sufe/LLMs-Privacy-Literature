# LLMs Privacy Literature

A curated list of LLMs security research
 papers.

Paper  are divided into three categories: motivation, possible dataset and methods design and sorted by their released dates in descending order.


## Quick Links
**Motivation:** [Link](#motivation-back-to-top)  
**Text Anonymization:** [Link](#text-anonymization-back-to-top)
**Style Transfer:** [Link](#style-transfer-back-to-top)
**Prompt attack:** [Link](#prompt-attack-back-to-top)  
**Jailbreak attack:** [Link](#jailbreak-attack-back-to-top)   
**De-identification and anonymization of medical reports:** [Link](#de-identification-and-anonymization-of-medical-reports-back-to-top)  
**Prompt Learning** [Link](#prompt-learning-back-to-top)   
**Text Generation** [Link](#text-generation-back-to-top)  

## Motivation [[Back to Top](#llms-privacy-literature)]

| Year   | Title |  Conference | Field  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2023 | **Beyond Memorization: Violating Privacy Via Inference with Large Language Models** | unknown | unknown | arXiv | [Link](https://arxiv.org/pdf/2310.07298v1.pdf) | unknown |
| 2023 | **DECODINGTRUST: A Comprehensive Assessment of Trustworthiness in GPT Models** | NeurIPS | unknown | arXiv | [Link](https://arxiv.org/pdf/2306.11698v4.pdf) | [Link](https://decodingtrust.github.io/) |
## Text Anonymization [[Back to Top](#llms-privacy-literature)]

| Year   | Title |  Conference | Field  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2021 | **ADePT: Auto-encoder based Differentially Private Text Transformation** | ACL2021 | DP(sentence level) | arxiv | [Link](https://arxiv.org/pdf/2102.01502.pdf) | [Link]( https://github.com/trusthlt/dp-rewrite) |
| 2022 | **DP-VAE: Human-Readable Text Anonymization for Online Reviews with Differentially Private Variational Autoencoders** | WWW’22 | DP(sentence level) | ACM | [Link](https://dl.acm.org/doi/10.1145/3485447.3512232) | unknown |
| 2022 | **A Customized Text Sanitization Mechanism with Differential Privacy** | ACL2023 | DP(token level) | arxiv | [Link](https://arxiv.org/pdf/2207.01193.pdf) | [Link]( https://github.com/sai4july/CusText) |
| 2023 | **Reducing Privacy Risks in Online Self-Disclosures with Language Models** | unknown | Finetune | arxiv | [Link](https://arxiv.org/pdf/2311.09538.pdf) | unknown |
| 2023 | **DP-BART for Privatized Text Rewriting under Local Differential Privacy** | ACL2023 | DP(sentence level) | arxiv | [Link](https://arxiv.org/pdf/2302.07636.pdf) | [Link](https://github.com/trusthlt/dp-bart-private-rewriting) |
| 2023 | **Locally Differentially Private Document Generation UsingZero Shot Prompting** | EMNLP | DP(word level) | arxiv | [Link](https://arxiv.org/pdf/2310.16111.pdf) | [Link](https://github.com/SaitejaUtpala/dp_prompt) |
| 2023 | ***InferDPT: Privacy-preserving Inference for Black-box Large Language Models*** | unknown | DP(token level) | arxiv | [Link](https://arxiv.org/pdf/2310.12214.pdf) | unknown |
| 2023 | **Differentially Private Natural Language Models: Recent Advances and Future Directions** | unknown | survey | arxiv | [Link](https://arxiv.org/pdf/2301.09112.pdf) | unknown|
| 2023 | **DEFENDING AGAINST AUTHORSHIP IDENTIFICATION ATTACKS** | unknown | survey | arxiv | [Link](https://arxiv.org/pdf/2310.01568.pdf) | unknown|


## Style Transfer [[Back to Top](#llms-privacy-literature)]
| Year   | Title |  Conference | Field  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2018 | **Delete, Retrieve, Generate:A Simple Approach to Sentiment and Style Transfer** | ACL | unknown | ACL | [Link](https://aclanthology.org/N18-1169.pdf) | [Link](https://github.com/lijuncen/Sentiment-and-Style-Transfer) |
| 2019 | **Disentangled Representation Learning for Non-Parallel Text Style Transfer** | ACL | Disentangle | ACL | [Link](https://aclanthology.org/P19-1041.pdf) | [Link](https://sites.google.com/view/disentangle4transfer)|

## Prompt attack [[Back to Top](#llms-privacy-literature)]

| Year   | Title |  Conference | Field  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2023 | **Prompt Injection Attacks and Defenses in LLM-Integrated Applications** | unknown | unknown | arXiv | [Link](https://arxiv.org/pdf/2310.12815.pdf) | [Link](https://github.com/liu00222/Open-Prompt-Injection) |
| 2023 | **PromptBench: Towards Evaluating the Robustness of Large Language Models on Adversarial Prompts** | unknown | unknown  | arXiv | [Link](https://arxiv.org/pdf/2306.04528.pdf) | [Link](https://github.com/microsoft/promptbench) |



## De-identification and anonymization of medical reports [[Back to Top](#llms-privacy-literature)]

| Year   | Title |  Conference | Field  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2023 | **Are Chatbots Ready for Privacy-Sensitive Applications? An Investigation into Input Regurgitation and Prompt-Induced Sanitization** | unknown | unknown | arXiv | [Link](https://arxiv.org/pdf/2305.15008.pdf) | unknown |
| 2023 | **DeID-GPT: Zero-shot Medical Text De-Identification by GPT-4** | unknown | unknown | arXiv | [Link](https://arxiv.org/pdf/2303.11032.pdf) | unknown |
  

## Jailbreak attack [[Back to Top](#llms-privacy-literature)]

| Year   | Title |  Conference | Field  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2023 | **ON THE SAFETY OF OPEN-SOURCED LARGE LANGUAGE MODELS: DOES ALIGNMENT REALLY PREVENT THEM FROM BEING MISUSED?** | unknown | Jailbreak  | arXiv | [Link](https://arxiv.org/pdf/2310.01581.pdf) | unknown |
| 2023 | **Do Anything Now”: Characterizing and Evaluating In-The-Wild Jailbreak Prompts on Large Language Models** | unknown | unknown | arXiv | unknown |
| 2023 | **MASTERKEY: Automated Jailbreaking of Large Language Model Chatbots** | unknown | unknown | arXiv | [Link](https://arxiv.org/pdf/2307.08715.pdf) | unknown | 
| 2023 | **Universal and Transferable Adversarial Attacks on Aligned Language Models** | unknown | unknown | arXiv | [Link](https://arxiv.org/pdf/2307.15043.pdf) | unknown | 
| 2023 | **SneakyPrompt: Jailbreaking Text-to-image Generative Models** | IEEE S&P 2024 | unknown | arXiv | [Link](https://arxiv.org/pdf/2305.12082.pdf) | [Link](https://github.com/Yuchen413/text2image-safety) | 
| 2024 | **How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety by Humanizing LLMs** | unknown | unknown | unknown | [Link](https://www.yi-zeng.com/wp-content/uploads/2024/01/view.pdf) | unknown | 
      
## Prompt Learning [[Back to Top](#llms-privacy-literature)]

| Year   | Title |  Conference | Field  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2021 | **The Power of Scale for Parameter-Efficient Prompt Tuning** | unknown | unknown  | arXiv | [Link](https://arxiv.org/pdf/2104.08691.pdf) | unknown |
| 2023 | **You Only Prompt Once: On the Capabilities of Prompt Learning on Large Language Models to Tackle Toxic Content?** | S&P | unknown  | arXiv | [Link](https://arxiv.org/pdf/2308.05596.pdf) | [Link](https://github.com/xinleihe/toxic-prompt) |

## Text Generation [[Back to Top](#llms-privacy-literature)]

| Year   | Title |  Conference | Type  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2021 | **Pretrained Language Models for Text Generation: A Survey** | ACM  | survey  | arxiv | [Link](https://arxiv.org/pdf/2201.05273.pdf) | unknown |
| 2021 | **Automatic text summarization: A comprehensive survey** | Expert Syst. Appl. (2021)| survey | ScienceDirect | [Link](https://www.sciencedirect.com/science/article/pii/S0957417420305030) | unknown |
| 2022 | **ParaDetox: Detoxification with Parallel Data** | ACL | paper  | acl | [Link](https://aclanthology.org/2022.acl-long.469.pdf) | unknown |
| 2023 | **A Systematic survey on automated text generation tools and techniques: application, evaluation, and challenges** | MULTIMED TOOLS APPL| survey | springer | [Link](https://link.springer.com/article/10.1007/s11042-023-15224-0) | unknown |
