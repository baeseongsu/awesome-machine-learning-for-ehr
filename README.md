# awesome-machine-learning-for-healthcare

Welcome to my personal repository, a curated collection of research works in machine learning for healthcare.
I welcome contributions and discussions, so feel free to share ideas or suggest papers!

## Large Language Models
### Model
- Hippocrates: An Open-Source Framework for Advancing Large Language Models in Healthcare, Acikgoz et al., 2024 [[paper]](https://arxiv.org/abs/2404.16621)
- Small Language Models Learn Enhanced Reasoning Skills from Medical Textbooks, Kim et al., 2024 [[paper]](https://arxiv.org/abs/2404.00376)
### Evaluation
<!--
QA benchmark
-->
- MedMCQA : A Large-scale Multi-Subject Multi-Choice Dataset for Medical domain Question Answering, Pal et al., 2022 [[paper]](https://arxiv.org/abs/2203.14371)
- K-QA: A Real-World Medical Q&A Benchmark, Manes et al., 2024 [[paper]](https://arxiv.org/abs/2401.14493)
- MedReadMe: A Systematic Study for Fine-grained Sentence Readability in Medical Domain, Jiang et al., 2024 [[paper]](https://arxiv.org/abs/2405.02144)

## Synthetic Data Generation
<!--
Synthetic EHR generation including table, notes, images ...
-->
- (2010/10) Data-driven approach for creating synthetic electronic medical records, Buczak et al., 2010 [[Paper]](https://pubmed.ncbi.nlm.nih.gov/20946670/)
- (2017/03) Generating Multi-label Discrete Patient Records using Generative Adversarial Networks, Choi et al., 2017 [[Paper]](https://arxiv.org/abs/1703.06490)
- (2023/03) EHRDiff: Exploring Realistic EHR Synthesis with Diffusion Models, Yuan and Zhou et al., 2023 [[Paper]](https://arxiv.org/abs/2303.05656)
- (2023/04) Synthesize High-dimensional Longitudinal Electronic Health Records via Hierarchical Autoregressive Language Model, Theodorou et al., 20223 [[Paper]](https://arxiv.org/abs/2304.02169)
- (2023/08) EHR-Safe: generating high-fidelity and privacy-preserving synthetic electronic health records, Yoon et al., 2023 [[Paper]](https://www.nature.com/articles/s41746-023-00888-7)


## Toward a Natural Language Interface for EHRs
<!-- 
question answering, summarization, dialogue, instructions, ...
-->
- (2015/03) Toward a Natural Language Interface for EHR Questions, Roberts and Demner-Fushman, 2015 [[Paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4525248/)
- (2016/05) Annotating logical forms for EHR questions, Roberts and Demner-Fushman, 2016 [[Paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5428549/)
- (2018/04) A Semantic Parsing Method for Mapping Clinical Questions to Logical Forms, Roberts and Demner-Fushman [[Paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5977685/)
- (2018/09) emrQA: A Large Corpus for Question Answering on Electronic Medical Records, Pampri et al., 2018 [[Paper]](https://arxiv.org/abs/1809.00732)
- (2019/08) Text-to-SQL Generation for Question Answering on Electronic Medical Records, Wang et al., 2019 [[Paper]](https://arxiv.org/abs/1908.01839)
- (2020/03) Using FHIR to Construct a Corpus of Clinical Questions Annotated with Logical Forms and Answers, Soni et al., 2020 [[Paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7153115/)
- (2020/05) Dataset and Enhanced Model for Eligibility Criteria-to-SQL Semantic Parsing, Yu et al., 2018 [[Paper]](https://aclanthology.org/2020.lrec-1.714/)
- (2020/05) Paraphrasing to improve the performance of Electronic Health Records Question Answering, Soni and Roberts, 2020 [[Paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7233085/)
- (2020/10) Knowledge Graph-based Question Answering with Electronic Health Records, Park et al., 2020 [[Paper]](https://arxiv.org/abs/2010.09394)
- (2021/06) emrKBQA: A Clinical Knowledge-Base Question Answering Dataset, Raghavan et al., 2021 [[Paper]](https://aclanthology.org/2021.bionlp-1.7/)
- (2021/11) Question Answering for Complex Electronic Health Records Database using Unified Encoder-Decoder Architecture, Bae et al., 2021 [[Paper]](https://arxiv.org/abs/2111.14703)
- (2022/03) Uncertainty-Aware Text-to-Program for Question Answering on Structured Electronic Health Records, Kim et al., 2022 [[Paper]](https://arxiv.org/abs/2203.06918)
- (2022/05) DrugEHRQA: A Question Answering Dataset on Structured and Unstructured Electronic Health Records For Medicine Related Queries, Bardhan et al., 2022 [[Paper]](https://arxiv.org/abs/2205.01290)
- (2022/06) Learning to Ask Like a Physician, Lehman et al., 2022 [[Paper]](https://arxiv.org/abs/2206.02696)
- (2022/06) RadQA: A Question Answering Dataset to Improve Comprehension of Radiology Reports, Soni et al., 2022 [[Paper]](https://aclanthology.org/2022.lrec-1.672/)
- (2023/01) EHRSQL: A Practical Text-to-SQL Benchmark for Electronic Health Records, Lee et al., 2023 [[Paper]](https://arxiv.org/abs/2301.07695)
- (2023/04) LeafAI: query generator for clinical cohort discovery rivaling a human programmer, Dobbins et al., 2023 [[Paper]](https://arxiv.org/abs/2304.06203)
- (2023/04) Toward a Neural Semantic Parsing System for EHR Question Answering, Soni and Roberts [[Paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10148366/)
- (2023/04) quEHRy: a question answering system to query electronic health records, Soni et al., 2023 [[Paper]](https://academic.oup.com/jamia/article-abstract/30/6/1091/7136720)
- (2023/06) ECG-QA: A Comprehensive Question Answering Dataset Combined With Electrocardiogram, Oh et al., 2023 [[Paper]](https://arxiv.org/abs/2306.15681)
- (2023/08) MedAlign: A Clinician-Generated Dataset for Instruction Following with Electronic Medical Records, Fleming et al., 2023 [[Paper]](https://arxiv.org/abs/2308.14089)
- (2023/09) Adapted Large Language Models Can Outperform Medical Experts in Clinical Text Summarization, Veen et al., 2023 [[Paper]](https://arxiv.org/abs/2309.07430)
- (2023/10) Question Answering for Electronic Health Records: A Scoping Review of datasets and models, Bardhan et al., 2023 [[Paper]](https://arxiv.org/abs/2310.08759)
- (2023/10) EHRXQA: A Multi-Modal Question Answering Dataset for Electronic Health Records with Chest X-ray Images, Bae and Kyung et al., 2023 [[Paper]](https://arxiv.org/abs/2310.18652)
- (2024/01) EHRAgent: Code Empowers Large Language Models for Few-shot Complex Tabular Reasoning on Electronic Health Records, Shi and Xu et al., 2024 [[Paper]](https://arxiv.org/abs/2401.07128)
- (2024/02) EHRNoteQA: A Patient-Specific Question Answering Benchmark for Evaluating Large Language Models in Clinical Settings, Kweon and Kim et al., 2024 [[Paper]](https://arxiv.org/abs/2402.16040)
- (2024/03) A Benchmark of Domain-Adapted Large Language Models for Generating Brief Hospital Course Summaries, Aali et al., 2024 [[Paper]](https://arxiv.org/abs/2403.05720)


## Medical Imaging
### medical imaging datasets
- (2019/12) MIMIC-CXR, a de-identified publicly available database of chest radiographs with free-text reports, Johnson et al., 2019 [[Paper]](https://www.nature.com/articles/s41597-019-0322-0)
- (2019/01) MIMIC-CXR-JPG, a large publicly available database of labeled chest radiographs, Johnson et al., 2019 [[Paper]](https://arxiv.org/abs/1901.07042)
- (2023/10) Towards long-tailed, multi-label disease classification from chest X-ray: Overview of the CXR-LT challenge, 2023 [[Paper]](https://arxiv.org/abs/2310.16112)
- (2024/04) RadGenome-Chest CT: A Grounded Vision-Language Dataset for Chest CT Analysis, Zhang et al., 2024 [[Paper]](https://arxiv.org/abs/2404.16754)

### radiology report generation
#### methodologies
- TBC
#### evaluation
- (2020/04) CheXbert: Combining Automatic Labelers and Expert Annotations for Accurate Radiology Report Labeling Using BERT, Smit, Jain and Rajpurkar et al., 2020 [[Paper]](https://arxiv.org/abs/2004.09167)
- (2021/06) RadGraph: Extracting Clinical Entities and Relations from Radiology Reports, Jain, Agrawal, and Saporta et al., 2021 [[Paper]](https://arxiv.org/abs/2106.14463)
- (2023/08) Radgraph2: Modeling disease progression in radiology reports via hierarchical information extraction, Khanna and Dejl et al., 2023 [[Paper]](https://arxiv.org/abs/2308.05046)
- (2023/09) Evaluating progress in automatic chest x-ray radiology report generation, Yu et al., 2023 [[Paper]](https://www.cell.com/patterns/pdf/S2666-3899(23)00157-5.pdf)
- (2023/11) Radiology-Aware Model-Based Evaluation Metric for Report Generation, Calamida et al., 2023 [[Paper]](https://arxiv.org/abs/2311.16764)
- (2024/04) LLM-RadJudge: Achieving Radiologist-Level Evaluation for X-Ray Report Generation, Wang et al., 2024 [[Paper]](https://arxiv.org/abs/2404.00998)
