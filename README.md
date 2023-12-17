# -Mistral-Llama-2-Orca-Yi-RAG

Excited to share my latest work using the powerful Llama2-13B-Chat,Mistral7B-Chat,Mixtral-8x7B,Orca-2-13B, Yi-34B LLMs for Retrieval Augmented Generation (RAG) with LlamaIndex! This notebook demonstrates how I leveraged Windows Subsystem for Linux (WSL) and Nvidia's CUDA to achieve impressive results.

Key highlights:

Environment: Windows 11, Anaconda environment, Nvidia RTX 3090
LLMs: Mistral 7B, Llama 2 13B Chat, Orca 2, Yi 34B (quantized versions)
Data: Word documents in the "Data" folder for RAG training
Package versions: Managed through conda and requirements.txt files
Local LLMs: Downloaded quantized models from huggingface.co (thanks, TheBloke!)
Important libraries: llama-cpp-python, transformers, llama-index, docx2txt, sentence-transformers
Conquering CUDA setup:

Getting CUDA libraries working under WSL was a bit tricky, but I followed these resources and emerged victorious:

CUDA Toolkit 12.3 installation guidance: https://docs.nvidia.com/cuda/wsl-user-guide/index.html
WSL-specific installation instructions: https://developer.nvidia.com/cuda-downloads?target_os=Linux&target_arch=x86_64&Distribution=WSL-Ubuntu&target_version=2.0&target_type=deb_local
Bonus tip: Use "nvidia-smi" in your WSL command prompt to confirm you're utilizing your Nvidia GPU and monitor its utilization during notebook execution.

Ready to explore further?

Check out the full notebook and resources for a deep dive into this exciting project! I'm eager to connect with other LLM enthusiasts and discuss the potential of Yi 34B and RAG. Feel free to leave comments, ask questions, and share your own LLM experiences!

#Yi34B #LLM #RAG #LlamaIndex #WSL #NvidiaCUDA #MachineLearning #AI

P.S. Don't forget to check out the main README for links to all the models I used!

I hope this post effectively summarizes your notebook's content for LinkedIn. Feel free to adjust the tone, add specific results or insights, and tailor it to your target audience. Good luck with your post!
