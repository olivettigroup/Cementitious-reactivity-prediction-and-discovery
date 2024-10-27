This repository contains the code and data associated with the research paper:

"Material discovery of secondary and natural cementitious precursors"

Authors: Soroush Mahjoubi, Vineeth Venugopal, Ipek Bensu Manav, Hessam Azarijafari, Randolph Kirchain, Elsa Olivetti

Cement production is a significant contributor to global greenhouse gas (GHG) emissions, primarily due to the production of clinker. This project aims to reduce these emissions by expanding the repertoire of secondary and natural cementitious precursors through data-driven, machine learning methods.

We developed models to predict the reactivity of cementitious materials and systematically identified potential substitutes for clinker, including secondary materials like construction and demolition wastes, and natural precursors such as rhyolite and basalt. Our approach combines large language models (LLMs) and multi-task neural networks to predict reactivity metrics, enabling the discovery of new materials that can reduce the GHG intensity of cement production.

Repository Contents
The repository is organized into Jupyter notebooks that sequentially perform the tasks described in the paper:

1_keyword_filtering_and_preprocessing.ipynb
Filters relevant literature using keywords and preprocesses the data for analysis.

2_Vector_database_for_tables.ipynb
Creates a vector database for tables extracted from the literature using embeddings.

3_Evaluation_of_table_embeddings.ipynb
Evaluates different embedding models for their effectiveness in retrieving relevant tables.

4_Table_extraction_with_fine-tuned_GPT_3.5.ipynb
Extracts chemical compositions from tables using a fine-tuned GPT-3.5 model.

4_Table_extraction_with_fine-tuned_Mistral_7b.ipynb
Alternative extraction of chemical compositions using a fine-tuned Mistral 7b model.

5_Evaluation_of_table_extraction.ipynb
Assesses the performance of the table extraction methods.

6_Vector_database_for_sentences.ipynb
Builds a vector database for sentences to aid in material classification.

7_Extraction_of_material_descriptors_with_Mistral_7b.ipynb
Extracts material descriptors using the Mistral 7b model.

8_Categorize_materials_with_fine-tuned_GPT_3.5.ipynb
Classifies materials into predefined categories using a fine-tuned GPT-3.5 model.

9_Train_the_multi-headed_NN_for_reactivity_prediction.ipynb
Trains a multi-headed neural network to predict reactivity metrics.

10_Reactivity_prediction_of_extracted_materials.ipynb
Predicts the reactivity of materials extracted from the literature.

11_Reactivity_prediction_of_natural_precursors.ipynb
Applies the trained model to predict the reactivity of natural rock samples.

