# llaman-prompting
Give a simple text description and have the model turn it into a prompt suitable for SD, Midjourney or DALLE


### Work in progress
- Creating a synthetic dataset containing 5k to 15k samples of prompt pairs
- Using Anthropic Claude-2 with 100k token context window to generate the dataset.
- Prompt engineering to find the prompt that outputs the best simple prompts (hardest part of the project actually)
- Fine-tuning a LLAMA2 13b model using this dataset on Replicate
- metadata.parquet is available [here]((https://huggingface.co/datasets/poloclub/diffusiondb/tree/main)https://huggingface.co/datasets/poloclub/diffusiondb/tree/main)


  
