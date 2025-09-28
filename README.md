# DreamOmni2
This project is the official implementation of 'DreamOmni2: Multimodal Instruction-based Editing and Generation''

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