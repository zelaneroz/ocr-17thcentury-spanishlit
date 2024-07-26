# Optical Character Recognition of 17th Century Spanish Literatyre using Convulutional-recurrent Architectures

**Task**: Build a model based on convolutional-recurrent architectures for optically recognizing text in the image dataset. Pick the most appropriate approach and discuss your strategy 

**Evaluation Metrics**: TBD

**Task & Data Source**: [HumanAI RenAIssance Project](https://humanai.foundation/gsoc/projects/2024/project_RenAIssance.html)

**Dataset**: [PDF text scans](text-extract.pdf)

**Dataset reference**: [Transcribed Text](text-transcription.docx)

**Dataset Description**
The dataset consist of 31 pages of a scanned early modern printed text. The image has a simple recognition applied that reflects the limitations of the OCR already used (missed letters, incorrectlly recognized words...), saved as a PDF file. The PDF is editable and can be saved as JPEGs if that helps with processing. Marginalia can be ignored and focus only on the main text which is organized in two columns per page. The dataset also contains a transcription of 25 pagaes - they should be used as reference while training the AI models for the project. The transcription also includes a few notes that should help manage expectations of slight variability in spelling errors or limitations throughout the text. The last 6 pages of transcriptions have been removed to later evaulate teh degree of accuracy and viability of the test method employed. 


**Other Tasks to try**
* Build model based on transformer architectures.
* Build a model based on self-supervised architectures.
