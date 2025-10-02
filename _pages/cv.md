<!--
Welcome to resume.lol !

This is the template you can use to get started.

Easily remove personal info by using a variable follow with a second value and "||":

@NAME=Real Name||Hidden Name

and change @REDACTED to be true

@REDACTED=true
-->
@REDACTED=false
@NAME=Chengyuan Zhang
@EMAIL=cyzhang0339@gmail.com
@PHONE=(425) 753-9631
@LINKEDIN=linkedin.com/in/chengyuan-zhang-0039z/

# {NAME} 
{PHONE} | {EMAIL} | [{LINKEDIN}](https://www.linkedin.com/in/chengyuan-zhang-0039z/)


### University of Maryland College Park - Computer Science, Mathematics  (2021 - 2025)

<div className="vertical-spacer"></div>

## Research
### Gamma Lab, UMIACS, UMCP — Undergraduate Research Assistant <span class="spacer"></span> Fall 2024 - Present
**DAVE: Diverse Atomic Visual Elements Dataset**

_Under review, preprint available on arXiv_
- Designed and implemented DAVE-DETR, a transformer-based detection model variant with a hierarchical query generator and redundant query reduction module, targeting small objects in complex scenarios.
- Benchmarked state-of-the-art detectors as baselines for DAVE, achieved SOTA performance of DAVE-DETR on DAVE (e.g., AP₅₀=0.292, ARₗ=0.712), outperforming YOLO and other existing DETR variants like Salience DETR and Deformable DETR (AP₅₀≈0.16-0.25).
- Built a YOLO-based pipeline to automatically blur sensitive information for privacy preservation in video data.  


**Bi-VLM: Ultra-Low Precision PTQ in VLMs**  

_Under review, preprint available on arXiv_
- Co-developed Bi-VLM, a post-training quantization method targeting ultra-low-bit (1 bit) for vision-language models (VLMs), improving performance by 4%-45% over SOTA quantizations.  
- Implemented ultra-low-bit quantization for baselines (AWQ, QVLM) and adapted major VLMs (LLaVA-Next, LLaMA, Qwen) for systematic benchmarking.


## Experiences
**Z.AI (AI Software Engineer, Intern)** <span class="spacer"></span> **June 2024 - August 2024**


- Optimized Retrieval-Augmented Generation (RAG) by integrating graph RAG and rank RAG, improving top-1 hit rate by 12% on large document collections.
- Implemented keyword and embedding indexing, improving retrieval accuracy across different data.
- Applied adapter/prefix fine-tuning on multimodal GLM4 for video-based reasoning, enhancing detection of dangerous construction behaviors and illegal fishing activities.
- Automated benchmarking process to measure hit rate and answer quality, reducing manual evaluation by 80% and enabling reproducible system comparisons.  

**Emotion Recognition (BitCamp Hackathon 2024)**  

- Built a video-based emotion recognition pipeline combining DETR for face detection and a CNN classifier (62% accuracy on FER2013), applied to analyze student engagement in exam settings.


<div className="vertical-spacer"></div>

## Projects
**AI Trip Planner** 
- Developed and deployed a language-model powered trip planner that generates itineraries from natural language queries, integrating a retrieval-augmented generation (RAG) over Wikivoyage.
- Optimized LangChain's retrieval API by parallelizing embedding calls, reduced retrieval latency and improved efficiency
- Implemented user management with JWT authentication, ensuring security and personalized access for users.

**Go Marketplace**
- Built a RESTful marketplace backend in Go (Gin, MongoDB) with JWT authentication, product/order management, and a real-time user-to-user live chat system.
- Trained a BERT-based embedding model on Kaggle's Online Sales dataset (masked language modeling) and integrated it into a hybrid recommendation system combining content-based and collaborative filtering for personalized product search.
- Automated API testing with Postman collections and custom test scripts, reducing manual effort by ~70%.

**Mini CFO Copilot**
- Built a VLM-powered financial analysis agent that answers natural language financial questions on revenue, gross margin, opex, EBITDA, and cash runway, using both textual/numerical data and chart visualizations.
- Designed a multi-step agent involving intent classification, structured JSON extraction (intent, time span, entity), data function calls, and final LLM response based on the functions return.
- Implemented comprehensive unit tests to validate data loading and financial calculations, ensuring correctness and reliability of agent outputs.


## Publications/Preprints
- Wang, X., Sandoval-Segura, P., Zhang, C., Huang, J., Guan, T., Xian, R., Liu, F., Chandra, R., Gong, B., & Manocha, D. DAVE: Diverse Atomic Visual Elements Dataset with High Representation of Vulnerable Road Users in Complex and Unpredictable Environments. arXiv preprint arXiv:2412.20042, 2024.
- Wang, X., Huang, J., Abdalla, R., Zhang, C., Xian, R., & Manocha, D. Bi-VLM: Pushing Ultra-Low Precision Post-Training Quantization Boundaries in Vision-Language Models. arXiv preprint 	arXiv:2509.18763, 2025.


<div className="vertical-spacer"></div>


