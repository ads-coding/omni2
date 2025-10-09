# DreamOmni2
This project is the official implementation of 'DreamOmni2: Multimodal Instruction-based Editing and Generation''

<a href="https://pbihao.github.io/projects/DreamOmni2/index.html"><img src="https://img.shields.io/badge/Project-Page-Green"></a>

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
