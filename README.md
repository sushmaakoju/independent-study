# Independent Study, Summer 2022, University of Colorado Boulder

## Study and design of NER & Text extraction from OCR scanned Handwritten Slave Trade Volumes

### Supervisors: Prof. Henry Lovejoy, Digital Slavery Research Lab, and Dr. Jane Wall, Faculty Director, Data Science

I worked on an Independent Study supervised by Prof. Henry Lovejoy for the Digital Slavery Research Lab, at the University of Colorado, Boulder. It was towards study and design of Named Entity Recognition from OCR scanned Handwritten Slave Trade Volumes and to train a search over OCR scanned documents. 

### Goal
The novel goal is that of not only emancipating Africans from
historical events and providing valuable insights, but also seems to indicate
a shift to emancipate from the present-day impressions of the past.
To analyze and emancipate people from present impressions of the past.

#### Acknowledgements:
Thanks to the <a href="https://www.colorado.edu/lab/dsrl/collaborators">Digital Slavery Research Lab/collaborators </a>.

- <a href="https://github.com/sushmaakoju/study-work-reports/blob/main/university-of-colorado-boulder/sushma-akoju-independent-study-digital-slavery-first_summary_report.pdf"> First report: study and design of Named Entity Extraction from OCR scanned Handwritten Slave Trade Volumes and to train a search over OCR scanned documents<a/>

- <a href="https://github.com/sushmaakoju/study-work-reports/blob/main/university-of-colorado-boulder/sushma-akoju-digital-slavery-project-indep_study_final_report.pdf"> Second report: study and design of Named Entity Extraction from OCR scanned Handwritten Slave Trade Volumes and to train a search over OCR scanned documents<a/>

- The challenge here was that Named Entity Recognition needs to run over the text extracted from the 19th-century English language text corpus. Performance over BERT under zero-shot settings was poor for 80% of the vocabulary. So we used <a href="https://github.com/sushmaakoju/macberth-eval">MacBERTh</a> model.

### Notebooks:

1. <a href="https://nbviewer.org/github/sushmaakoju/named-entity-text-extraction-ocr-slave-trade-volumes/blob/main/extract_from_listofpapers_june17.ipynb">Extracting "List of papers" Pages using Tesseract and Transkribus manual annotations for Regions of Interest (ROI) for layout segmentations</a>

2. <a href="https://nbviewer.org/github/sushmaakoju/named-entity-text-extraction-ocr-slave-trade-volumes/blob/main/automated_annotation_layout_parser_segmentation.ipynb"> Zero-shot layout segmentation annotations evaluation</a>

3. <a href="https://github.com/sushmaakoju/named-entity-text-extraction-ocr-slave-trade-volumes/blob/main/sushma_akoju_july_19_class_A_analysis.ipynb">Text extraction with Google Document AI API and text extraction over class **A** documents, Slave trade volumes</a>

4. <a href="https://github.com/sushmaakoju/named-entity-text-extraction-ocr-slave-trade-volumes/blob/main/sushma_akoju_july_20_class_B_analysis.ipynb">Text extraction with Google Document AI API and text extraction over class **B** documents, Slave trade volumes</a>

5. <a href="https://github.com/sushmaakoju/named-entity-text-extraction-ocr-slave-trade-volumes/blob/main/sushma_akoju_pos_analysis.ipynb">Annotating IOB tags from Parts-of-speech tags and Named Entities from ground truth over-extracted text from OCR scanned Handwritten Slave Trade Volumes</a>

### Historical newspapers data studied under Digital Humanities: HIPE (Identifying Historical People, Places and other Entities)

Here are full details hopefully, helpful for Text Segmentation from Impresso project, Identifying Historical People, Places and other Entities from Digital Humanities. 

- This is the paper: Extended Overview of CLEF HIPE 2020: Named Entity Processing on Historical Newspapers  Page 8 about Annotation for Segmentation, Page 17 about Types of Segmentations that contain coarse information, Page 19 SBB and Page 24 with evaluation results.
- Github: <a href="https://github.com/eldams/mXS">mXS</a>
- <a href="https://impresso.github.io/CLEF-HIPE-2020/">https://impresso.github.io/CLEF-HIPE-2020/</a>

"CLEF-HIPE-2020 (Identifying Historical People, Places and other Entities) is a evaluation campaign on named entity processing on historical newspapers in French, German and English, organized in the context of the impresso project and run as a CLEF 2020 Evaluation Lab." (Project: <a href="https://github.com/impresso/CLEF-HIPE-2020/blob/master/evaluation-results/ranking_summary_final.md">Impresso CLEFiHIPE ranking summary</a>)

- The architecture from: <a href="https://www.youtube.com/watch?v=BOu5Wk3wrDo&list=PLB45F159nVx-3bee7G_1jdTfUAtsLD0FU&index=2">The architecture with Sentence Segmentation</a>
- <a href="https://www.youtube.com/playlist?list=PLB45F159nVx9CwVvXx1vYEBN--BWHurnn">Impresso project short video playlist</a>
- This is the repository: <a href="https://github.com/impresso/CLEF-HIPE-2020/tree/master/data">https://github.com/impresso/CLEF-HIPE-2020/tree/master/data</a>
- This is the specific video about annotations of segments for context from INRIA, paris : <a href="https://www.youtube.com/watch?v=tx95NRcnTuU&list=PLB45F159nVx-3bee7G_1jdTfUAtsLD0FU">https://www.youtube.com/watch?v=tx95NRcnTuU&list=PLB45F159nVx-3bee7G_1jdTfUAtsLD0FU</a>
- From LMU, Germany: <a href="https://www.youtube.com/watch?v=TyxvRjdt9Vs&list=PLB45F159nVx-3bee7G_1jdTfUAtsLD0FU&index=3">https://www.youtube.com/watch?v=TyxvRjdt9Vs&list=PLB45F159nVx-3bee7G_1jdTfUAtsLD0FU&index=3</a>
- <a href="https://www.youtube.com/watch?v=boz0LrheVP0&list=PLB45F159nVx-3bee7G_1jdTfUAtsLD0FU&index=8">Entity Linking Pipeline from Impresso project</a>
- One of the full implementation pipelines from HIPE (that I studied for my independent study): <a href="https://www.youtube.com/watch?v=RtcgbH0kVF8&list=PLB45F159nVx-3bee7G_1jdTfUAtsLD0FU&index=10">HIPE</a>
