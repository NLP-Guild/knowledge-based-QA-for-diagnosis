# Knowledge-based-QA-for-Diagnosis
Knowledge Graph,Question Answering System，基于知识图谱和向量检索的医疗诊断问答系统

[[doc](https://easydoc.net/doc/84261587/TevBXTHz/gsaJm7M6)] 

# 1 Model Structure
![](https://i.imgur.com/FYBIzv8.png)


# 2 Reproduction & Workflow
## Full reproduction (build from scratch): 
1. build knowledge graph [[colab](https://colab.research.google.com/gist/leoxiang66/bf52b9045187a95e276914451954c667/build_kg.ipynb)]
2. build NER dataset [[colab](https://colab.research.google.com/gist/leoxiang66/a50ea0713cd9e99daa4734f1e61ce5c8/build-ner-dataset.ipynb)]
3. train NER model [[train](https://colab.research.google.com/gist/leoxiang66/6510451934d15703a80c73b401c87a1a/finetune-chinese-bert-ner-biomedical.ipynb)] [[inference](https://colab.research.google.com/gist/leoxiang66/f77e7b6d893276a6bb68ffd7951f2ffa/untitled46.ipynb)] [[model on Huggingface](https://huggingface.co/Adapting/bert-base-chinese-finetuned-NER-biomedical)]
4. train intent-recognition model [[train](https://colab.research.google.com/gist/leoxiang66/89484e1e8fd8ad5fdc2acd13c4580fee/train-bert-intent-recognition-biomedical.ipynb)]
5. entity-linking logic [[colab](https://colab.research.google.com/gist/leoxiang66/482c4c20e0945b7a150f8a95a00b14d9/entity_linking_text-similarity.ipynb)]

## Minimal reproduciton (direct usage)

# 3 Reference
1. https://github.com/wangle1218/KBQA-for-Diagnosis


