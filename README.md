This notebook has 4 different ways to execute different quantized versions of LLMs.
1. There is CTransformers way along with langchain to execute the GGUF quantized models.
2. There is some models (like : MPT-7B) that needs to be executed with Ctransformer but not with Langchain.
3. There are models which are not supported in CTransformer like Phi model from Microsoft, but supported by Llama cpp.
4. There are models that are small and quantized versions are not required, which can be executed using transformer library directly.
Hope this notebook helps you in executing the model of your choice on your local machine.
