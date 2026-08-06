AMedRAG-V1: This is a RAG system for Medical application(Version1).
这是一个医疗应用场景下专用的RAG系统。  
本项目代码由两个ipynb文件组成，rag_da.ipynb是数据分析模块，rag_query.ipynb是RAG主模块，上传至AutoDL等算力云平台即可运行（4090单卡即可）。  
模型可选Deepseek-R1-7B或Deepseek-R1-8B,也可以根据个人喜好选择Qwen2.5或Qwen3。  
嵌入模型可选ollama或BGE-small    
本项目使用的大模型和嵌入模型均来自Huggingface。  
搭建知识库用到的医疗文献源数据来自：https://ftp.ncbi.nlm.nih.gov/pub/pmc/oa_bulk/  
这里我们只使用了oa_comm中的部分文献，如果您的算力资源和设备更强，可以选择更大的数据集。   
如果数据集链接无法打开，您可以下载我们上传到其他平台的数据(即将更新)，并直接上传到算力云平台进行使用;    
首先在终端输入激活命令: source activate med_rag
