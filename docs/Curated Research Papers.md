# Essential LLM + Transformer Papers (Links + quick context)

A curated “build-the-core-first” reading list: Transformers → scaling → efficient attention → RAG → instruction tuning → reasoning/agents → MoE → interpretability.
(Compiled on 2026-02-12.)

---

## Recommended reading order (1–26)

1) **Attention Is All You Need** (Vaswani et al., 2017)  
   - arXiv: https://arxiv.org/abs/1706.03762  
   - PDF: https://arxiv.org/pdf/1706.03762.pdf  
   - (Classic Transformer: self-attention, multi-head attention, encoder–decoder.)

2) **The Illustrated Transformer** (Jay Alammar, 2018)  
   - Article: https://jalammar.github.io/illustrated-transformer/  
   - (Best “intuition first” walkthrough before you implement.)

3) **BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding** (Devlin et al., 2018)  
   - arXiv: https://arxiv.org/abs/1810.04805  
   - PDF: https://arxiv.org/pdf/1810.04805.pdf  
   - Code (official, archived): https://github.com/google-research/bert  

4) **Language Models are Few-Shot Learners (GPT‑3)** (Brown et al., 2020)  
   - arXiv: https://arxiv.org/abs/2005.14165  
   - PDF: https://arxiv.org/pdf/2005.14165.pdf  
   - (No official training code release; useful “big-picture” capability paper.)

5) **Scaling Laws for Neural Language Models** (Kaplan et al., 2020)  
   - arXiv: https://arxiv.org/abs/2001.08361  
   - PDF: https://arxiv.org/pdf/2001.08361.pdf  

6) **Training Compute‑Optimal Large Language Models (Chinchilla)** (Hoffmann et al., 2022)  
   - arXiv: https://arxiv.org/abs/2203.15556  
   - PDF: https://arxiv.org/pdf/2203.15556.pdf  

7) **LLaMA: Open and Efficient Foundation Language Models** (Touvron et al., 2023)  
   - arXiv: https://arxiv.org/abs/2302.13971  
   - PDF: https://arxiv.org/pdf/2302.13971.pdf  
   - Inference starter code (Meta): https://github.com/meta-llama/llama  

8) **RoFormer: Enhanced Transformer with Rotary Position Embedding (RoPE)** (Su et al., 2021)  
   - arXiv: https://arxiv.org/abs/2104.09864  
   - PDF: https://arxiv.org/pdf/2104.09864.pdf  

9) **FlashAttention: Fast and Memory‑Efficient Exact Attention with IO‑Awareness** (Dao et al., 2022)  
   - arXiv: https://arxiv.org/abs/2205.14135  
   - PDF: https://arxiv.org/pdf/2205.14135.pdf  
   - Code (official): https://github.com/Dao-AILab/flash-attention  

10) **Retrieval‑Augmented Generation (RAG)** (Lewis et al., 2020)  
   - arXiv: https://arxiv.org/abs/2005.11401  
   - PDF: https://arxiv.org/pdf/2005.11401.pdf  
   - Practical ref implementation (Transformers RAG): https://huggingface.co/docs/transformers/model_doc/rag  

11) **Training Language Models to Follow Instructions with Human Feedback (InstructGPT)** (Ouyang et al., 2022)  
   - arXiv: https://arxiv.org/abs/2203.02155  
   - PDF: https://arxiv.org/pdf/2203.02155.pdf  

12) **Direct Preference Optimization (DPO)** (Rafailov et al., 2023)  
   - arXiv: https://arxiv.org/abs/2305.18290  
   - PDF: https://arxiv.org/pdf/2305.18290.pdf  

13) **Chain‑of‑Thought Prompting Elicits Reasoning in Large Language Models** (Wei et al., 2022)  
   - arXiv: https://arxiv.org/abs/2201.11903  
   - PDF: https://arxiv.org/pdf/2201.11903.pdf  

14) **ReAct: Synergizing Reasoning and Acting in Language Models** (Yao et al., 2022 / ICLR 2023)  
   - arXiv: https://arxiv.org/abs/2210.03629  
   - PDF: https://arxiv.org/pdf/2210.03629.pdf  
   - Code (prompting repo): https://github.com/ysymyth/ReAct  
   - Project site: https://react-lm.github.io/  

15) **DeepSeek‑R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning** (Guo et al., 2025)  
   - arXiv: https://arxiv.org/abs/2501.12948  
   - PDF: https://arxiv.org/pdf/2501.12948.pdf  
   - Code/models (official): https://github.com/deepseek-ai/DeepSeek-R1  

16) **Qwen3 Technical Report** (Yang et al., 2025)  
   - arXiv: https://arxiv.org/abs/2505.09388  
   - PDF: https://arxiv.org/pdf/2505.09388.pdf  
   - GitHub (official): https://github.com/QwenLM/Qwen3  

17) **Outrageously Large Neural Networks: Sparsely‑Gated Mixture‑of‑Experts** (Shazeer et al., 2017)  
   - arXiv: https://arxiv.org/abs/1701.06538  
   - PDF: https://arxiv.org/pdf/1701.06538.pdf  

18) **Switch Transformers** (Fedus et al., 2021)  
   - arXiv: https://arxiv.org/abs/2101.03961  
   - PDF: https://arxiv.org/pdf/2101.03961.pdf  

19) **Mixtral of Experts** (Jiang et al., 2024)  
   - arXiv: https://arxiv.org/abs/2401.04088  
   - PDF: https://arxiv.org/pdf/2401.04088.pdf  
   - Official inference lib (Mistral): https://github.com/mistralai/mistral-inference  

20) **Sparse Upcycling: Training Mixture‑of‑Experts from Dense Checkpoints** (Komatsuzaki et al., 2022 / ICLR 2023)  
   - arXiv: https://arxiv.org/abs/2212.05055  
   - PDF: https://arxiv.org/pdf/2212.05055.pdf  

21) **The Platonic Representation Hypothesis** (Huh et al., 2024)  
   - arXiv: https://arxiv.org/abs/2405.07987  
   - PDF: https://arxiv.org/pdf/2405.07987.pdf  

22) **Textbooks Are All You Need** (Gunasekar et al., 2023)  
   - arXiv: https://arxiv.org/abs/2306.11644  
   - PDF: https://arxiv.org/pdf/2306.11644.pdf  

23) **Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet** (Templeton et al., 2024)  
   - Article / thread: https://transformer-circuits.pub/2024/scaling-monosemanticity/  

24) **PaLM: Scaling Language Modeling with Pathways** (Chowdhery et al., 2022)  
   - arXiv: https://arxiv.org/abs/2204.02311  
   - PDF: https://arxiv.org/pdf/2204.02311.pdf  

25) **GLaM: Efficient Scaling of Language Models with Mixture‑of‑Experts** (Du et al., 2021/2022)  
   - arXiv: https://arxiv.org/abs/2112.06905  
   - PDF: https://arxiv.org/pdf/2112.06905.pdf  

26) **The Smol Training Playbook** (Hugging Face, 2025)  
   - Main: https://huggingface.co/spaces/HuggingFaceTB/smol-training-playbook  
   - TOC: https://huggingface.co/spaces/HuggingFaceTB/smol-playbook-toc  

---

## Bonus material (5)

A) **T5: Exploring the Limits of Transfer Learning with a Unified Text‑to‑Text Transformer** (Raffel et al., 2019)  
   - arXiv: https://arxiv.org/abs/1910.10683  
   - PDF: https://arxiv.org/pdf/1910.10683.pdf  
   - Code (official): https://github.com/google-research/text-to-text-transfer-transformer  

B) **Toolformer: Language Models Can Teach Themselves to Use Tools** (Schick et al., 2023)  
   - arXiv: https://arxiv.org/abs/2302.04761  
   - PDF: https://arxiv.org/pdf/2302.04761.pdf  
   - Community code: https://github.com/conceptofmind/toolformer  

C) **GShard: Scaling Giant Models with Conditional Computation and Automatic Sharding** (Lepikhin et al., 2020)  
   - arXiv: https://arxiv.org/abs/2006.16668  
   - PDF: https://arxiv.org/pdf/2006.16668.pdf  

D) **Adaptive Mixtures of Local Experts** (Jacobs et al., 1991)  
   - PDF (Hinton lab mirror): https://www.cs.toronto.edu/~fritz/absps/jjnh91.pdf  

E) **Hierarchical Mixtures of Experts and the EM Algorithm** (Jordan & Jacobs, 1994)  
   - PDF (Hinton lab mirror): https://www.cs.toronto.edu/~hinton/absps/hme.pdf  

---

## Tiny note (so you don’t get stuck)
Some papers (e.g., GPT‑3) don’t have an “official training repo” you can clone. In those cases, treat the arXiv as the source of truth, and use modern open implementations (Transformers, Megatron‑LM style stacks, etc.) for the engineering.
"""
