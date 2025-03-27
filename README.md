# Script

<https://github.com/jgoodyear/ollama-benchmark.git>

# System Information

Ubuntu 22.04 LTS

Intel Xeon E-2378

DDR4 ECC 3200 MT.

NVidia RTX 1000 ADA.

8 GB vram.

## Model: LLAMA 3.2 (2.0GB)

    Model
        architecture        llama
        parameters          3.2B
        context length      131072
        embedding length    3072
        quantization        Q4_K_M

      Parameters
        stop    "<|start_header_id|>"
        stop    "<|end_header_id|>"
        stop    "<|eot_id|>"

      License
        LLAMA 3.2 COMMUNITY LICENSE AGREEMENT
        Llama 3.2 Version Release Date: September 25, 2024

| Queue Size | Context Size | Requests | Number of Parallel Model Requests Allowed | Duration (Seconds) | Errors | Notes |
|----|----|----|----|----|----|----|
| 512 | 2048 | 128 | 128 |  |  | Did not run on GPU |
| 512 | 2048 | 128 | 16 | 370 | 0 | Memory Usage: 7.014Gi/7.996Gi |
| 512 | 2048 | 128 | 8 | 379 | 0 | Memory Usage: 4.771Gi/7.996Gi |
| 512 | 2048 | 128 | 4 | 427 | 0 | Memory usage: 3.506Gi/7.996Gi |
| 512 | 2048 | 128 | 2 | 520 | 0 | Memory usage: 2.904Gi/7.996Gi |
| 512 | 2048 | 128 | 1 | 795 | 0 | Memory usage: 2.682Gi/7.996Gi |

| Queue Size | Context Size | Requests | Number of Parallel Model Requests Allowed | Duration (Seconds) | Errors | Notes |
|----|----|----|----|----|----|----|
| 512 | 4096 | 128 | 128 |  |  | Did not run on GPU |
| 512 | 4096 | 128 | 16 | 348 | 0 | Memory Usage: 7.018Gi/7.996Gi |
| 512 | 4096 | 128 | 8 | 387 | 0 | Memory Usage: 4.773Gi/7.996Gi |
| 512 | 4096 | 128 | 4 | 425 | 0 | Memory Usage: 3.506Gi/7.996Gi |
| 512 | 4096 | 128 | 2 | 521 | 0 | Memory Usage: 2.902Gi/7.996Gi |
| 512 | 4096 | 128 | 1 | 777 | 0 | Memory Usage: 2.686Gi/7.996Gi |

| Queue Size | Context Size | Requests | Number of Parallel Model Requests Allowed | Duration (Seconds) | Errors | Notes |
|----|----|----|----|----|----|----|
| 512 | 131072 | 128 | 128 |  |  | Did not run on GPU |
| 512 | 131072 | 128 | 16 | 358 | 0 | Memory Usage: 7.018Gi/7.996Gi |
| 512 | 131072 | 128 | 8 | 389 | 0 | Memory Usage: 4.775Gi/7.996Gi |
| 512 | 131072 | 128 | 4 | 429 |  | Memory Usage: 3.506Gi/7.996Gi |
| 512 | 131072 | 128 | 2 | 508 | 0 | Memory Usage: 2.902Gi/7.996Gi |
| 512 | 131072 | 128 | 1 | 789 | 0 | Memory Usage: 2.686Gi/7.996Gi |

## DeepSeek-R1:7b (4.7 GB)

    Model
        architecture        qwen2
        parameters          7.6B
        context length      131072
        embedding length    3584
        quantization        Q4_K_M

      Parameters
        stop    "<｜begin▁of▁sentence｜>"
        stop    "<｜end▁of▁sentence｜>"
        stop    "<｜User｜>"
        stop    "<｜Assistant｜>"

      License
        MIT License
        Copyright (c) 2023 DeepSeek

| Queue Size | Context Size | Requests | Number of Parallel Model Requests Allowed | Duration (Seconds) | Errors | Notes |
|----|----|----|----|----|----|----|
| 512 | 131072 | 128 | 128 |  |  | Did not run on GPU |
| 512 | 2048 | 128 | 16 | 3409 | 0 | Memeory Usage: 6.891Gi/7.996Gi |
| 512 | 2048 | 128 | 8 | 3014 | 0 | Memeory Usage: 6.225Gi/7.996Gi |
| 512 | 2048 | 128 | 4 | 2377 | 0 | Memory Usage: 5.332Gi/7.996Gi |
| 512 | 2048 | 128 | 2 | 2547 | 0 | Memory Usage: 4.928Gi/7.996Gi |
| 512 | 2048 | 128 | 1 | 3877 | 0 | Memory Usage: 4.818Gi/7.996Gi |

## DeepSeek-R1:1.5b (1.1 GB)

    Model
        architecture        qwen2
        parameters          1.8B
        context length      131072
        embedding length    1536
        quantization        Q4_K_M

      Parameters
        stop    "<｜begin▁of▁sentence｜>"
        stop    "<｜end▁of▁sentence｜>"
        stop    "<｜User｜>"
        stop    "<｜Assistant｜>"

      License
        MIT License
        Copyright (c) 2023 DeepSeek

| Queue Size | Context Size | Requests | Number of Parallel Model Requests Allowed | Duration (Seconds) | Errors | Notes |
|----|----|----|----|----|----|----|
| 512 | 131072 | 128 | 128 |  |  | Did not run on GPU |
| 512 | 2048 | 128 | 16 | 45 | 0 | Memory Usage: 2.961Gi/7.996Gi |
| 512 | 2048 | 128 | 8 | 93 | 0 | Memory Usage: 2.113Gi/7.996Gi |
| 512 | 2048 | 128 | 4 | 95 | 0 | Memory Usage: 1.766Gi/7.996Gi |
| 512 | 2048 | 128 | 2 | 117 | 0 | Memory Usage: 1.656Gi/7.996Gi |
| 512 | 2048 | 128 | 1 | 169 | 0 | Memory Usage: 1.602Gi/7.996Gi |

## mistral 7.2b (4.1 GB)

    Model
        architecture        llama
        parameters          7.2B
        context length      32768
        embedding length    4096
        quantization        Q4_0

      Parameters
        stop    "[INST]"
        stop    "[/INST]"

      License
        Apache License
        Version 2.0, January 2004

| Queue Size | Context Size | Requests | Number of Parallel Model Requests Allowed | Duration (Seconds) | Errors | Notes |
|----|----|----|----|----|----|----|
| 512 | 131072 | 128 | 128 |  |  | Did not run on GPU |
| 512 | 2048 | 128 | 16 | 424 | 0 | Memory Usage: 7.342Gi/7.996Gi |
| 512 | 2048 | 128 | 8 | 194 | 0 | Memory Usage: 7.168Gi/7.996Gi |
| 512 | 2048 | 128 | 4 | 204 | 0 | Memory Usage: 5.650Gi/7.996Gi |
| 512 | 2048 | 128 | 2 | 304 | 0 | Memory Usage: 4.893Gi/7.996Gi |
| 512 | 2048 | 128 | 1 | 576 | 0 | Memory Usage: 4.514Gi/7.996Gi |
