# Standalone-Annotation-Tool

## Tool Description

This tool is named Boğaziçi University Annotation Tool (BoAT). BoAT is a desktop annotation tool which is specifically designed for dependency parsing and supports the CoNLL-U format. Annotation tools are fundamental to the facilitation of the annotation process of many NLP tasks including dependency parsing. BoAT offers both tree view and table view for the dependency parse of a sentence. In the tree view, the sentence is visualized in the form of a graph. In the table view, the sentence is shown along with its default fields which are ID, FORM, LEMMA, UPOS, XPOS, FEATS, HEAD, DEPREL, DEPS, and MISC. Annotators can customize the table view according to their needs.

This tool was referenced by the paper:  
Türk, U., Atmaca, F., Özateş, Ş.B. et al. Resources for Turkish dependency parsing: introducing the BOUN Treebank and the BoAT annotation tool. Lang Resources & Evaluation 56, 259–307 (2022). https://doi.org/10.1007/s10579-021-09558-0

## Installation and Running

This tool easily can be built with the following instructions:

1. Obtain the code using one of the following methods:
* Download https://github.com/boun-tabilab-dip/Standalone-Annotation-Tool/archive/refs/heads/main.zip and unzip
OR
* Use git `git clone https://github.com/boun-tabilab-dip/Standalone-Annotation-Tool.git`
2. Go to the newly created directory (if using zip the directory should be 'Standalone-Annotation-Tool-main'. If using git the directory should be 'Standalone-Annotation-Tool').
3. Install the dependencies by `pip install -r requirements.txt`
4. Run the tool with the command `python main.py`
