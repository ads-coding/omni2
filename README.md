# DreamOmni2: Multimodal Instruction-based Editing and Generation

<p align="center">
    <a href="https://arxiv.org/html/2510.06679v1">
            <img alt="Build" src="https://img.shields.io/badge/arXiv%20paper-2510.06679v1-b31b1b.svg">
    </a>
    <a href="https://pbihao.github.io/projects/DreamOmni2/index.html">
        <img alt="Project Page" src="https://img.shields.io/badge/Project-Page-blue">
    </a>
    <a href="">
        <img alt="Build" src="https://img.shields.io/badge/DreamOmni2-Benchmark-green">
    </a>
    <a href="">
        <img alt="Build" src="https://img.shields.io/badge/🤗-HF%20Model-yellow">
    </a>    
    <a href="">
        <img alt="Build" src="https://img.shields.io/badge/🤗-HF%20Demo-yellow">
    </a>
</p>

## 🔥 News
- **2025.6.26**: Release DreamOmni2 tech report.


[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/8xpoiRK57uU/0.jpg)](https://www.youtube.com/watch?v=8xpoiRK57uU)










## Web Demo
```
CUDA_VISIBLE_DEVICES=0 python web_edit.py \
    --vlm_path PATH_TO_VLM \
    --edit_lora_path PATH_TO_DEIT_LORA \
    --server_name "0.0.0.0" \
    --server_port 7860


CUDA_VISIBLE_DEVICES=1 python web_generate.py \
    --vlm_path PATH_TO_VLM \
    --gen_lora_path PATH_TO_GENERATION_LORA \
    --server_name "0.0.0.0" \
    --server_port 7861
```
