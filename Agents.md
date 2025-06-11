## REPO STRUCTURE

The root of the project has a directory called `nemo_rl` with the following 
structure:


- __init__.py
- package_info.py
algorithms/
  - __init__.py
  - dpo.py
  - grpo.py
  - interfaces.py
  - loss_functions.py
  - sft.py
  - utils.py
converters/
  - __init__.py
  huggingface/
    - __init__.py
    - vllm_export.py
  megatron/
    - __init__.py
    - vllm_export.py
data/
  - __init__.py
  - datasets.py
  - interfaces.py
  - llm_message_utils.py
  hf_datasets/
    - __init__.py
    - chat_templates.py
    - deepscaler.py
    - dpo.py
    - helpsteer3.py
    - oasst.py
    - openmathinstruct2.py
    - prompt_response_dataset.py
    - squad.py
distributed/
  - __init__.py
  - batched_data_dict.py
  - collectives.py
  - model_utils.py
  - named_sharding.py
  - ray_actor_environment_registry.py
  - virtual_cluster.py
  - worker_groups.py
environments/
  - __init__.py
  - interfaces.py
  - math_environment.py
  - metrics.py
  - utils.py
  games/
    - sliding_puzzle.py
evals/
  - __init__.py
  - eval.py
experience/
  - __init__.py
  - rollouts.py
metrics/
  - __init__.py
  - metrics_utils.py
models/
  - __init__.py
  dtensor/
    - __init__.py
    - parallelize.py
  generation/
    - __init__.py
    - interfaces.py
    - vllm.py
    - vllm_backend.py
  huggingface/
    - __init__.py
    - common.py
  megatron/
    - __init__.py
    - common.py
  policy/
    - __init__.py
    - dtensor_policy_worker.py
    - fsdp1_policy_worker.py
    - hf_policy.py
    - interfaces.py
    - utils.py
utils/
  - __init__.py
  - checkpoint.py
  - config.py
  - logger.py
  - native_checkpoint.py
  - nvml.py
  - timer.py
  - venvs.py


