# A Catalog for Indic LLM Resources
The purpose of this catalog is to help researchers looking for Indic LLM resources. This is a collective effort and any contribution to enriching Indic LLM resources is welcome. All contributors are listed on the <a href="https://github.com/shantipriyap/IndicLLM_Resource_Catalog/blob/main/CONTRIBUTORS.md">CONTRIBUTOR</a> list. 

Table of Contents
=================
* [Instruction Set](#instruction-set)
* [Fine-Tuned LLM](#fine-tuned-llm)
* [Pre-trained LLM](#pre-trained-llm)

### Instruction Set
#### Odia
* <a href="https://huggingface.co/datasets/OdiaGenAI/odia_master_data_llama2">odia_master_data_llama2</a>: This dataset contains 180k Odia instruction sets translated from open-source instruction sets and Odia domain knowledge instruction sets.
* <a href="https://huggingface.co/datasets/OdiaGenAI/odia_context_10K_llama2_set">odia_context_10k_llama2_set</a>: This dataset contains 10K instructions that span various facets of Odisha's unique identity. The instructions cover a wide array of subjects, ranging from the culinary delights in 'RECIPES,' the historical significance of 'HISTORICAL PLACES,' and 'TEMPLES OF ODISHA,' to the intellectual pursuits in 'ARITHMETIC,' 'HEALTH,' and 'GEOGRAPHY.' It also explores the artistic tapestry of Odisha through 'ART AND CULTURE,' which celebrates renowned figures in 'FAMOUS ODIA POETS/WRITERS', and 'FAMOUS ODIA POLITICAL LEADERS'. Furthermore, it encapsulates 'SPORTS' and the 'GENERAL KNOWLEDGE OF ODISHA,' providing an all-encompassing representation of the state.

#### Bengali
* <a href="https://huggingface.co/datasets/OdiaGenAI/all_combined_bengali_252k">all_combined_bengali_252K</a>: This dataset is a mix of Bengali instruction sets translated from open-source instruction sets: Dolly, Alpaca, ChatDoctor, Roleplay, and GSM.

#### Hindi
* <a href="https://huggingface.co/datasets/OdiaGenAI/hindi_alpaca_dolly_67k_formatted">hindi_alpaca_dolly_67k_formatted</a>: This dataset is translated from open-source Alpaca_Dolly instruction sets.
* <a href="https://huggingface.co/datasets/OdiaGenAI/instruction_set_hindi_1035">instruction_set_hindi_1035</a>: The dataset has been created using OliveFarm web application.
The domains have been covered in this dataset are: Art, Sports (Cricket, Football, Olympics), Politics, History, Cooking, Environment, Music

### Fine-Tuned LLM

#### Odia
* <a href="https://huggingface.co/OdiaGenAI/odia_llama2_7B_base">odia_llama2_7B_base</a>: odia_llama2_7B_base is based on Llama2-7b and finetuned with 180k Odia instruction set.<a href="https://arxiv.org/pdf/2312.12624.pdf">Paper</a>

#### Hindi
* <a href="https://huggingface.co/OdiaGenAI/mistral_hindi_7b_base_v1">mistral_hindi_7b_base_v1 </a>: mistral_hindi_7b_base_v1 is based on Mistral_7b and finetuned with the Hindi instruction set.

#### Bengali
* <a href="https://huggingface.co/OdiaGenAI/odiagenAI-bengali-base-model-v1">odiagenAI-bengali-base-model-v1</a>: odiagenAI-bengali-base-model-v1 is based on Llama-7b and finetuned with 252k Bengali instruction set. The instruction set is translated data from open-source resources, resulting in good Bengali instruction understanding and response generation capabilities.

