# Data Science and Investment Research
**Technical Skills:** TensorFlow,NumPy, Pandas, Scikit-learn, R, SQL/NoSQL, Snowflake, SPSS, JMP/JSL, VBA, Hypothesis Testing, Regression Analysis, Experimental Design, PowerBI, Exploratory Data Analysis, Classification, LLMs

## Education
- Philosophy, BA
- Biology, BS
- HuggingFace: https://huggingface.co/JuIm

## Work Experience
#### ***Quantitative and Fundamental Fixed Income Researcher @ Conning Inc. (August 2022 - Present)***

- Built ensemble AI credit rating models (MLPs) using TensorFlow to quantify fundamental credit risk, enabling faster and more precise investment decisions as well as potentially expanding coverage
- Architected a proof-of-concept ETL pipeline using Snowflake and Snowpark to ingest market data and generate actionable trading signals, resulting in broader market coverage and improved price discovery
- Created a proof-of-concept AI pipeline using Llama 2 and AbstractCRE, streamlining research and amplifying productivity by generating credit and ESG comments
- Prepared and presented detailed investment recommendations, memos, credit comments, and sector reports for the firm’s strategy meetings
- Reviewed and interpreted complex legal documentation such as bond indentures and credit agreements to understand structures, covenants, and associated risks
- Conducted investment research, financial analysis, and wrote in-depth reports on $7B in Municipals encompassing high yield, structured, and investment grade debt
- Performed analyses on financial and ESG datasets to identify statistically significant trading signals and created portfolio construction frameworks to evaluate signals

#### ***Data Analyst @ Boehringer Ingelheim (March 2022 - August 2022)***

- Provided ongoing maintenance, support, and enhanced functionality for a globally used data quality assurance tool in Excel/Access VBA to ensure application reliability and a smooth user experience
- Streamlined operational workflows through task automation using Excel VBA to drive efficiency and better utilization of resources

## Research Experience
#### ***Student Researcher @ UConn Health -- Behavioural Sciences***

- Investigated the relationships between facial flushing after the consumption of alcohol and various biometrics such as BP and HbA1c
- Research resulted in a peer-reviewed publication

#### ***Student Researcher @ Quinnipiac University -- Environmental Sciences***

- Investigated the effects of 'forever chemicals' on HEK 293 cell growth

#### ***Student Researcher @ Yale School of Medicine -- Neuropsychiatry***

- Researched the effects of flavorants and nicotine concentration on nicotine intake in rats via intra-oral and intra-venous self administration
- Work resulted in several peer-reviewed publications

## Completed Data Science and Artifical Intelligence Projects
#### ***ProGemma - A Gemma 2 LLM Pre-Trained on Amino Acid Sequences of Length 0 - 512***
- Trained a custom configuration (275M) of the Gemma 2 LLM to generate novel amino acid sequences on a letter-by-letter basis, a key application in protein engineering
- Built a custom BPE tokenizer to ensure efficient model training
- Preliminary evaluation of generated sequences on AlphaFold 3 (AlphaFold Server) indicates pTM scores of around 0.5 and PLDDT scores > 60
- Model improvements by using control tags is currently being investigated
  
#### ***ViT_Skin_Cancer – Fine Tuned ViT on Skin Cancer Images***
- Fine-tuned a ViT (google/vit-base-patch16-224) on a collection of benign and cancerous skin cancer photographs
- Open-sourced the model on Hugging Face for public use and commentary
  
#### ***ViT_Breast_Cancer – Fine Tuned ViT on Breast Cancer Microscope Images***
- Fine-tuned a ViT (google/vit-base-patch16-224) on a collection of approximately 7000 images of benign and cancerous breast tissue samples
- Achieved strong performance with a loss of 0.007 in classifying malignant and benign tissues, potentially aiding in more accurate diagnoses
- Open-sourced the model on Hugging Face for public use and commentary
  
#### ***SMILES_BERT -- A RoBERTa model Fine-Tuned on Chemical SMILES***
- Trained a custom configuration of a RoBERTa model on a dataset of chemical SMILES strong to bridge the gap between natural language processing and drug discovery
- Created and trained a custom Byte Pair Encoding (BPE) tokenizer to better handle the unique vocabulary, resulting in the elimination of ‘<unk> ’tokens
- Customized the configuration of the base model to achieve a better compromise between available compute and model performance
- Open-sourced the model on HuggingFace, achieving 3000+ downloads showing a contribution to the advancement of the computational biology/chemistry research

#### ***Fixed Income Portfolio Optimizer***
- Built a portfolio optimizer using the PuLP library in Python for fixed income instruments that maximizes portfolio yield for a given ratings, convexity, and duration target
- The optimizer supplements discretionary portfolio construction with data-driven portfolio insights, which allows for more guided and precise decision making
- Allows for a more streamlined implementation of specific portfolio strategies such as barbells, bullets, or ladders
  
#### ***Monte Carlo DCF Framework***
- Built a DCF framework in Python that utilizes Monte Carlo methods to simulate valuations given normally distributed EBITDA Margins, Revenue Growth, and Net Working Capital

## Projects to be Completed by Year End 2024
#### ***OncoVision -- Cancer Identification in Microscope Slide Images***
- Breaking ground on training/fine-tuning vision models (CNNs and ViTs) to identify different types of cancer from microscope slides
- This project is essentially an extension of my pre-exisiting ViT_Breast Cancer model that I envision turning into a broad research tool
- Currently in the data collection phase

#### ***Bond Retriever -- RAG Agent for Municipal Bond Documents***
- Building a RAG application utilizing LlamaIndex, Llama 2, and an open-source embedding model that is being fine-tuned on QA pairs from municipal bond documents
- Currently generating thousands of QA pairs from hundreds on bond documents using gemini-flash

## Publications
*Citroen, K. & **Immanuel, J.** (2024). State of the States: Municipal Bond Credit Perspectives [White paper]. Conning Inc. 
https://www.conning.com/-/media/marketingsite/documents/state-of-the-states/state-of-the-states-2024.pdf*

*Citroen, K. & **Immanuel, J.** (2023). State of the States: Municipal Bond Credit Perspectives [White paper]. Conning Inc. https://www.conning.com/-/media/marketingsite/documents/state-of-the-states/state-of-the-states---2023.pdf*

*Feinn, R., Bermudez-Millan, A., Berthold, S. M., Buckley, T., **Immanuel, J.**, Fraser-King, L., Horn, I. S., Keuky, L., Kong, S., Kuoch, T., O'Donnell, S., Read, J. P., Scully, M., & Wagner, J. (2021). Relationship of alcohol use and facial flushing to blood pressure and hba1c among Cambodian populations with dysglycemia in the U.S. and in Cambodia. Diabetes & Metabolic Syndrome: Clinical Research & Reviews, 102374. https://doi.org/10.1016/j.dsx.2021.102374*

*Bagdas D, Rupprecht LE, Nunes EJ, Schillinger E, **Immanuel JJ**, Addy NA. Effects of Cherry and Vanilla Flavorants on Oral Nicotine Liking and Disliking in Rats. In: The Society for Research on Nicotine and Tobacco 26th Annual Meeting; 2020 Mar 11-14; New Orleans, LA. https://cdn.ymaws.com/www.srnt.org/resource/resmgr/conferences/2020_annual_meeting/SRNT20_Abstracts_NEW_0227202.pdf*

*Bagdas, D., Rupprecht, L. E., Nunes, E. J., Schillinger, E., **Immanuel, J. J.**, & Addy, N. A. (2021). Evaluation of Flavor Effects on Oral Nicotine Liking and/or Disliking Using the Taste Reactivity Test in Rats. Nicotine & Tobacco Research. https://doi.org/10.1093/ntr/ntab241*




