
<div align="center">
<h2 align="center">
   <img src="./assets/mirage.png" style="vertical-align: middle; height: 1em; padding: 0 0.2em;"> <b>Mirage-1: Augmenting and Updating GUI Agent with 
     <br />  Hierarchical Multimodal Skills
</h2>
<div>
<a target="_blank" href="https://scholar.google.com/citations?user=KO77A2oAAAAJ&hl=en">Yuquan&#160;Xie</a><sup>1</sup>,
<a target="_blank" href="https://scholar.google.com/citations?user=TDBF2UoAAAAJ&hl=en&oi=ao">Zaijing&#160;Li</a><sup>1 2</sup>,
<a target="_blank" href="https://scholar.google.com/citations?user=9Vc--XsAAAAJ&hl=en&oi=ao">Rui&#160;Shao</a><sup>1&#9993</sup>,
<a target="_blank" href="https://scholar.google.com/citations?user=Mpg0w3cAAAAJ&hl=en&oi=ao">Gongwei&#160;Chen</a><sup>1</sup>,
<br>
<a target="_blank" href="https://scholar.google.com/citations?hl=en&user=Awsue7sAAAAJ">Dongmei&#160;Jiang</a><sup>2</sup>,
<a target="_blank" href="https://scholar.google.com/citations?hl=en&user=nHmlZ5QAAAAJ">Kaiwen&#160;Zhou</a><sup>3</sup>,
  <a target="_blank" href="https://scholar.google.com/citations?user=M6YfuCTSaKsC&hl=en">Yinchuan&#160;Li</a><sup>3</sup>,
 <a target="_blank" href="https://scholar.google.com/citations?hl=en&user=yywVMhUAAAAJ">Liqiang&#160;Nie</a><sup>1&#9993</sup>
</div>
<sup>1</sup>Harbin Institute of Technology,Shenzhen&#160&#160&#160</span>
<sup>2</sup>Peng Cheng Laboratory&#160&#160&#160</span>
<sup>3</sup>Huawei Noah's Ark Lab</span>
<br />
<sup>&#9993&#160;</sup>Corresponding author&#160;&#160;</span>
<br/>
<div align="center">
    <a href="https://arxiv.org/abs/2502.19902" target="_blank">
    <img src="https://img.shields.io/badge/Paper-arXiv-deepgreen" alt="Paper arXiv"></a>
    <a href="https://cybertronagent.github.io/Mirage-1.github.io/" target="_blank">
    <img src="https://img.shields.io/badge/Project-Mirage--1-9cf" alt="Project Page"></a>
</div>
</div>

## :balloon: Framework
A: The architecture of Optimus-3, which includes a task router that selects a specific task expert for each query, a ViT for visual encoding, and a MoE LLM for generating responses and low-level actions. Given a long-horizon task, it can generate a feasible plan and then execute the sub-goals sequentially. B: The proposed Multimodal Reasoning-Augmented Reinforcement Learning effectively enhances the agent's performance. C: Performance comparison of Optimus-3 against current task-specific SOTA agents, GPT-4o, and the original backbone Qwen2.5-VL. 
<img src="./assets/fig1.png" >

## :smile_cat: Evaluation results

Table 1: Performance comparison on AndroidWorld, MobileMiniWob++, and AndroidLH.
<img src="./assets/table1.png" >

## Conclusion
In this paper, we propose a Hierarchical Multimodal Skills module (HMS) that addresses the challenge of insufficient prior knowledge in long-horizon task planning. To address the domain gap between offline and online, a Skill-Augmented Monte Carlo Tree Search (SA-MCTS) algorithm is proposed. This algorithm effectively utilizes offline-acquired skills to reduce the action search space during online tree exploration. On top of HMS, we propose multimodal agent Mirage-1. Experimental results demonstrate that Mirage-1 achieves superior performance compared to SOTA GUI agents, particularly in long-horizon tasks.







