Apple M4

## Model: LLAMA 3.2 (2.0GB)

```
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
```

| Queue Size | Context Size | Requests | Number of Parallel Model Requests Allowed | Duration (Seconds) | Errors | Notes |
|----|----|----|----|----|----|----|
| 512 | 2048 | 128 | 128 |  |  |  |
| 512 | 2048 | 128 | 64 | 3780 | 0 | Memory Usage: 9.895Gi/16.000Gi |
| 512 | 2048 | 128 | 32 | 864 | 0 | Memory Usage: 9.386Gi/16.000Gi |
| 512 | 2048 | 128 | 16 | 413 | 0 | Memory Usage: 7.274Gi/16.000Gi |
| 512 | 2048 | 128 | 8 | 899 | 0 | Memory Usage: 4.743Gi/16.000Gi |
| 512 | 2048 | 128 | 4 | 940 | 0 | Memory usage: 3.477Gi/16.000Gi |
| 512 | 2048 | 128 | 2 | 948 | 0 | Memory usage: 2.876Gi/16.000Gi |
| 512 | 2048 | 128 | 1 | 1116 | 0 | Memory usage: 2.657Gi/16.000Gi |


## Model: Mistral (4.1GB)
```
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
```

| Queue Size | Context Size | Requests | Number of Parallel Model Requests Allowed | Duration (Seconds) | Errors | Notes |
|----|----|----|----|----|----|----|
| 512 | 2048 | 128 | 128 |  |  |  |
| 512 | 2048 | 128 | 64 | n/a | 1 | failed to allocate Metal buffer of size 8891928576 |
| 512 | 2048 | 128 | 32 | 656 | 0 | Memory Usage: 9.894Gi/16.000Gi |
| 512 | 2048 | 128 | 16 | 250 | 0 | Memory Usage: 10.127Gi/16.000Gi |
| 512 | 2048 | 128 | 8 | 706 | 0 | Memory Usage: 7.096Gi/16.000Gi |
| 512 | 2048 | 128 | 4 | 650 | 0 | Memory usage: 5.580Gi/16.000Gi |
| 512 | 2048 | 128 | 2 | 752 | 0 | Memory usage: 4.822Gi/16.000Gi |
| 512 | 2048 | 128 | 1 | 883 | 0 | Memory usage: 4.453Gi/16.000Gi|


## Model: Deepseek-R1 1.5b (1.1GB)
```
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
```

| Queue Size | Context Size | Requests | Number of Parallel Model Requests Allowed | Duration (Seconds) | Errors | Notes |
|----|----|----|----|----|----|----|
| 512 | 2048 | 128 | 128 |  |  | Could not run 128 runners. |
| 512 | 2048 | 128 | 64 | 65 | 0 | Memory Usage: 8.070Gi/16.000Gi |
| 512 | 2048 | 128 | 32 | 61 | 0 | Memory Usage: 4.695Gi/16.000Gi |
| 512 | 2048 | 128 | 16 | 74 | 0 | Memory Usage: 3.008Gi/16.000Gi |
| 512 | 2048 | 128 | 8 | 160 | 0 | Memory Usage:  2.164Gi/16.000Gi |
| 512 | 2048 | 128 | 4 | 160 | 0 | Memory usage: 1.820Gi/16.000Gi |
| 512 | 2048 | 128 | 2 | 167 | 0 | Memory usage: 1.711Gi/16.000Gi |
| 512 | 2048 | 128 | 1 | 220 | 0 | Memory usage: 1.656Gi/16.000Gi|



## Model: Deepseek-R1 7b (4.7 GB)
```
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
```

| Queue Size | Context Size | Requests | Number of Parallel Model Requests Allowed | Duration (Seconds) | Errors | Notes |
|----|----|----|----|----|----|----|
| 512 | 2048 | 128 | 128 |  |  | Could not run 128 runners. |
| 512 | 2048 | 128 | 64 |  | 0 | Memory Usage:  |
| 512 | 2048 | 128 | 32 |  | 0 | Memory Usage:  |
| 512 | 2048 | 128 | 16 | 2791 | 0 | Memory Usage:  |
| 512 | 2048 | 128 | 8 |  | 0 | Memory Usage:   |
| 512 | 2048 | 128 | 4 |  | 0 | Memory usage: 5.547Gi/16.000Gi |
| 512 | 2048 | 128 | 2 | 5212 | 0 | Memory usage: 5.145Gi/16.000Gi |
| 512 | 2048 | 128 | 1 | 5903 | 0 | Memory usage: 5.036Gi/16.000Gi|


## Model: GandalfBaum/llama3.1-claude3.7 (4.9 GB)
```
Model
    architecture        llama     
    parameters          8.0B      
    context length      131072    
    embedding length    4096      
    quantization        Q4_K_M    

  Parameters
    stop    "<|start_header_id|>"    
    stop    "<|end_header_id|>"      
    stop    "<|eot_id|>"             

  System
    The assistant is Claude, created by Anthropic.    
    The current date is {{currentDateTime}}.          

  License
    LLAMA 3.1 COMMUNITY LICENSE AGREEMENT            
    Llama 3.1 Version Release Date: July 23, 2024
```
| Queue Size | Context Size | Requests | Number of Parallel Model Requests Allowed | Duration (Seconds) | Errors | Notes |
|----|----|----|----|----|----|----|
| 512 | 2048 | 128 | 128 |  |  | Could not run 128 runners. |
| 512 | 2048 | 128 | 64 |  | 0 | Memory Usage:  |
| 512 | 2048 | 128 | 32 |  | 0 | Memory Usage:  |
| 512 | 2048 | 128 | 16 |  | 0 | Memory Usage:  |
| 512 | 2048 | 128 | 8 |  | 0 | Memory Usage:   |
| 512 | 2048 | 128 | 4 |  | 0 | Memory usage: |
| 512 | 2048 | 128 | 2 |  | 0 | Memory usage:  |
| 512 | 2048 | 128 | 1 | 2917 | 0 | Memory usage: 5.076Gi/16.000Gi|


