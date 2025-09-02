# The-Art-of-Analyzing-Big-Data-Project
This repository is part of the "The Art of Analyzing Big Data" class project.


In some files the preview of the notebook dosent work, however it can still be download and view in Colab.


Files Order and Explantion:
1. PDF Conversion (extract_images_from_pdf): Each magazine issue PDF was converted into individual page images, ensuring high-quality outputs suitable for OCR and visual analysis.
2. Ad Page Classification (classify_images): Utilized edge-detection and size heuristics to distinguish pages with single versus multiple advertisements, clustering images accordingly.
3. Ad Cropping and Preprocessing (single_ads_preprocesse, multi_preprocess): Pages classified as containing single or multiple ads were processed to crop individual ads and remove marginal and footer elements, accounting for variations in page layout.
4. Feature Extraction and NLP (extract_features_from_images): Each extracted ad image processed with text recognition (Tesseract OCR for Hebrew and English) and feature extraction. Then implemented advanced Hebrew NLP (including AlephBERT, sentiment and entity recognition), visual analysis (dominant colors, object and symbol detection), and categorical classification.
5. Statistical and Visual Analysis (ads_analysis): The processed dataset was summarized and visualized, including distributions of product categories, gender targeting, pricing structures, holiday timing, and geographic information.
