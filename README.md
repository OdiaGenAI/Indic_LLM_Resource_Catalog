# A Catalog for Indic LLM Resources
This catalog aims to assist researchers seeking Indic LLM resources. It's a collaborative endeavor, and any input to enhance the collection of Indic LLM resources is appreciated. All contributors have acknowledged on the <a href="https://github.com/shantipriyap/IndicLLM_Resource_Catalog/blob/main/CONTRIBUTORS.md">CONTRIBUTOR</a> list. 

<p align="center">
<img src="https://github.com/shantipriyap/Indic_LLM_Resource_Catalog/blob/main/magnifying-glass-7544299_1280.png" alt="llm_resource_catalog" width="250"/>
</p>

Table of Contents
=================
- [1. Instruction Set](#instruction-set)
  * [1.1 Odia](#odia)
  * [1.2 Bengali](#bengali)
  * [1.3 Hindi](#hindi)
  * [1.4 Kannada](#kannada)
  * [1.5 Punjabi](#punjabi)
  * [1.6 Telugu](#telugu)
  * [1.7 Indic](#indic)      
- [2. Pre-train Dataset](#pre-train-data-set)
  * [2.1 Indic](#indic)
- [3. Foundation LLM](#foundation-llm)
  * [3.1 Hindi](#hindi)
  * [3.2 Tamil](#tamil)
  * [3.3 Marathi](#marathi)
  * [3.4 Odia](#odia)
- [4. Fine-Tuned LLM](#fine-tuned-llm)
  * [4.1 Odia](#odia)
  * [4.2 Hindi](#hindi)
  * [4.3 Bengali](#bengali)   
- [5. Benchmarking Set](#benchmarking-set)


## Instruction Set
### Odia
* <a href="https://huggingface.co/datasets/OdiaGenAI/odia_master_data_llama2">odia_master_data_llama2</a>: This dataset contains 180k Odia instruction sets translated from open-source instruction sets and Odia domain knowledge instruction sets.
* <a href="https://huggingface.co/datasets/OdiaGenAI/odia_context_10K_llama2_set">odia_context_10k_llama2_set</a>: This dataset contains 10K instructions that span various facets of Odisha's unique identity. The instructions cover a wide array of subjects, ranging from the culinary delights in 'RECIPES,' the historical significance of 'HISTORICAL PLACES,' and 'TEMPLES OF ODISHA,' to the intellectual pursuits in 'ARITHMETIC,' 'HEALTH,' and 'GEOGRAPHY.' It also explores the artistic tapestry of Odisha through 'ART AND CULTURE,' which celebrates renowned figures in 'FAMOUS ODIA POETS/WRITERS', and 'FAMOUS ODIA POLITICAL LEADERS'. Furthermore, it encapsulates 'SPORTS' and the 'GENERAL KNOWLEDGE OF ODISHA,' providing an all-encompassing representation of the state.
* <a href="https://huggingface.co/datasets/OdiaGenAI/roleplay_odia">roleplay_odia</a>: This dataset contains 1k Odia role play instruction set in conversation format.
* <a href="https://huggingface.co/datasets/OdiaGenAI/OdiEnCorp_translation_instructions_25k">OdiEnCorp_translation_instructions_25k</a>: This dataset contains 25k English-to-Odia translation instruction set.

### Bengali
* <a href="https://huggingface.co/datasets/OdiaGenAI/all_combined_bengali_252k">all_combined_bengali_252K</a>: This dataset is a mix of Bengali instruction sets translated from open-source instruction sets: Dolly, Alpaca, ChatDoctor, Roleplay, and GSM.

### Hindi
* <a href="https://huggingface.co/datasets/OdiaGenAI/hindi_alpaca_dolly_67k_formatted">hindi_alpaca_dolly_67k_formatted</a>: This dataset is translated from open-source Alpaca_Dolly instruction sets.
* <a href="https://huggingface.co/datasets/OdiaGenAI/instruction_set_hindi_1035">instruction_set_hindi_1035</a>: The dataset has been created using OliveFarm web application.
The domains that have been covered in this dataset are Art, Sports (Cricket, Football, Olympics), Politics, History, Cooking, Environment, and Music.
* <a href="https://huggingface.co/datasets/OdiaGenAI/roleplay_hindi">roleplay_hindi</a>: The dataset contains 1k Hindi roleplay instruction set.
* <a href="https://huggingface.co/datasets/OdiaGenAI/sentiment_analysis_hindi">sentiment_analysis_hindi</a>: This dataset contains 2.5k Hindi sentiment analysis instruction set.

### Kannada
* <a href="https://huggingface.co/datasets/Tensoic/airoboros-3.2_kn">airoboros-3.2_kn</a>: This dataset contains 35.5k number of Kannada instruction (input, instruction, output) sets.

### Punjabi
* <a href="https://huggingface.co/datasets/HydraIndicLM/punjabi_alpaca_52K">punjabi_alpaca_52K</a>: This dataset contains 52k number of Punjabi instruction (input, instruction, output) sets translated from Alpaca.

### Telugu
* <a href="https://huggingface.co/datasets/HydraIndicLM/telgu_alpaca_dolly_67k">telgu_alpaca_dolly_67k</a>: This dataset contains 67k number of Telugu instruction (input, instruction, output) sets translated from Alpaca and Dolly.

### Indic
* <a href="https://huggingface.co/datasets/CohereForAI/aya_dataset">aya_dataset</a>: This dataset contains instruction sets in different Indic languages (Hindi, Tamil, Punjabi, Telugu, Marathi, Gujarati, Malayalam, Bengali). <a href="https://arxiv.org/pdf/2402.06619.pdf">Paper</a>

## Pe-train Dataset
### Indic
* <a href="https://huggingface.co/datasets/uonlp/CulturaX">CulturaX</a>: It is a multilingual dataset contains monolingual data for several Indic languages (Hindi, Bangla, Tamil, Malayalam, Marathi, Telugu, Kannada, Gujarati, Punjabi, Odia, Assamese, etc.). <a href="https://arxiv.org/abs/2309.09400">Paper</a>
* <a href="https://huggingface.co/datasets/rahular/varta">varta</a>: The dataset contains 41.8 million news articles in 14 Indic languages and English, crawled from DailyHunt, a popular news aggregator in India that pulls high-quality articles from multiple trusted and reputed news publishers.

## Foundation LLM

### Hindi
* <a href="https://huggingface.co/sarvamai/OpenHathi-7B-Hi-v0.1-Base">OpenHathi-7B-Hi-v0.1-Base</a>: This is a 7B parameter, based on Llama2, trained on Hindi, English, and Hinglish. As per the authors, this is a base model and is not meant to be used as is. Recommend to first fine-tune the interested task(s). <a href="https://www.sarvam.ai/blog/announcing-openhathi-series">Blog</a>

### Tamil
* <a href="https://huggingface.co/abhinand/tamil-llama-7b-base-v0.1">Tamil LLaMA 7B Base v0.1</a>: This is a 7B parameter model for Causal LM pre-trained on CulturaX dataset's Tamil subset. <a href="https://arxiv.org/pdf/2311.05845.pdf">Arxiv Paper</a>

### Marathi
* <a href="https://huggingface.co/marathi-llm/MahaMarathi-7B-v24.01-Base">MahaMarathi-7B-v24.01-Base</a>: This is a domain adapted, continually pre-trained, and instruction fine-tuned native Marathi large language model (LLM) with 7 billion parameters based on Llama2+Mistral, and trained on a large corpus of Marathi text. As per the authors, it is a model is a base model and not meant to be used as is. It is recommended to first finetune it on downstream tasks.

### Odia
* <a href="https://huggingface.co/OdiaGenAI-LLM/qwen_1.5_odia_7b">Qwen_1.5_Odia_7B</a>: This is a pre-trained Odia large language model with 7 billion parameters, and it is based on Qwen 1.5-7B. The model is pre-trained on the Culturex-Odia dataset, a filtered version of the original CulturaX dataset for Odia text. As per the authors, it is a model is a base model and not meant to be used as is. It is recommended to first finetune it on downstream tasks. <a href="https://www.odiagenai.org/blog/introducing-odiagenai-s-qwen-based-pre-trained-llm-for-odia-language">Blog</a>

## Fine-Tuned LLM

### Odia
* <a href="https://huggingface.co/OdiaGenAI/odia_llama2_7B_base">odia_llama2_7B_base</a>: odia_llama2_7B_base is based on Llama2-7b and finetuned with 180k Odia instruction set. <a href="https://arxiv.org/pdf/2312.12624.pdf">Paper</a>

### Hindi
* <a href="https://huggingface.co/OdiaGenAI/mistral_hindi_7b_base_v1">mistral_hindi_7b_base_v1 </a>: mistral_hindi_7b_base_v1 is based on Mistral_7b and finetuned with the Hindi instruction set.

### Bengali
* <a href="https://huggingface.co/OdiaGenAI/odiagenAI-bengali-base-model-v1">odiagenAI-bengali-base-model-v1</a>: odiagenAI-bengali-base-model-v1 is based on Llama-7b and finetuned with 252k Bengali instruction set. The instruction set is translated data from open-source resources, resulting in good Bengali instruction understanding and response generation capabilities. <a href="https://www.odiagenai.org/blog/odiagenai-released-an-instruction-following-llama-model-for-bengali">Blog</a>

### Benchmarking Set
* <a href="https://huggingface.co/collections/ai4bharat/airavata-evaluation-suite-65b13b7b68165de71ba0b333">Airavata Evaluation Suite</a>: A collection of benchmarks used for evaluation of Airavata, a Hindi instruction-tuned model on top of Sarvam's OpenHathi base model.
* <a href="https://huggingface.co/Indic-Benchmark">Indic LLM Benchmark</a>: A collection of LLM benchmark data in Gujurati, Nepali, Malayalam, Hindi, Telugu, Marathi, Kannada, Bengali.


Citation:

If you find this repository useful, please consider giving ⭐ and citing:

```
@misc{Indic_LLM_Resources,
  author = {Shantipriya Parida and Sambit Sekhar},
  title = {Indic LLM Resource Catalog},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/shantipriyap/Indic_LLM_Resource_Catalog}},
}
```
## License

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

