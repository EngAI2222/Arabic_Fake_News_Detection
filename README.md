نبذة عن المشروع | Project Overview
English
This project presents a Deep Learning based Natural Language Processing (NLP) system designed to detect fake Arabic news articles.
The system analyzes Arabic textual data and classifies news into Real or Fake using an LSTM neural network.
Fake news has become a major problem in the digital age, especially with the rapid spread of misinformation through social media platforms.
This project aims to build an intelligent system capable of detecting misleading Arabic news automatically.
العربية
يقدم هذا المشروع نظامًا يعتمد على التعلم العميق ومعالجة اللغات الطبيعية (NLP) للكشف عن الأخبار المزيفة باللغة العربية.
يقوم النظام بتحليل النصوص الإخبارية العربية وتصنيفها إلى أخبار حقيقية أو أخبار مزيفة باستخدام نموذج LSTM.
تعد الأخبار المزيفة مشكلة كبيرة في العصر الرقمي بسبب انتشار المعلومات المضللة عبر وسائل التواصل الاجتماعي، لذلك يهدف هذا المشروع إلى بناء نظام ذكي قادر على اكتشاف الأخبار المضللة تلقائيًا.

######################################################################################################################
أهداف المشروع | Project Objectives
English
Detect fake Arabic news articles.
Apply NLP techniques for Arabic text processing.
Train a Deep Learning model for classification.
Evaluate the model performance using different metrics.
العربية
الكشف عن الأخبار المزيفة باللغة العربية.
تطبيق تقنيات معالجة اللغات الطبيعية على النصوص العربية.
تدريب نموذج تعلم عميق لتصنيف الأخبار.
تقييم أداء النموذج باستخدام عدة مقاييس.
التقنيات المستخدمة | Technologies Used
نسخ التعليمات البرمجية
Text
Python
Natural Language Processing (NLP)
TensorFlow / Keras
Scikit-learn
Pandas
NumPy
Matplotlib
Jupyter Notebook
########################################################################################################################
مراحل المشروع | Project Pipeline
English
The system follows several steps:
Data Collection
Text Cleaning
Tokenization
Text to Numerical Representation
Padding Sequences
Train/Test Split
LSTM Model Training
Model Evaluation
العربية
يمر المشروع بعدة مراحل رئيسية:
جمع البيانات
تنظيف النصوص
تقسيم النص إلى كلمات
تحويل النصوص إلى أرقام
توحيد طول النصوص
تقسيم البيانات إلى تدريب واختبار
تدريب نموذج LSTM
تقييم النموذج

####################################################################################################################
هيكل النموذج | Model Architecture
English
The Deep Learning model architecture includes:
Embedding Layer
LSTM Layer
Dropout Layer
Dense Layer
Sigmoid Output Layer
العربية
يتكون نموذج التعلم العميق من الطبقات التالية:
طبقة Embedding
طبقة LSTM
طبقة Dropout
طبقة Dense
طبقة الإخراج باستخدام Sigmoid

####################################################################################################################
نتائج النموذج | Model Performance
English
The trained model achieved high performance:
نسخ التعليمات البرمجية
Text
Accuracy: 99%
Evaluation metrics include:
Accuracy
Precision
Recall
F1-score
Confusion Matrix
العربية
حقق النموذج دقة عالية في التنبؤ:
نسخ التعليمات البرمجية
Text
الدقة: 99%
كما تم تقييم النموذج باستخدام:
الدقة (Accuracy)
الاسترجاع (Recall)
الدقة الإيجابية (Precision)
مقياس F1
مصفوفة الالتباس (Confusion Matrix)
مثال على التنبؤ | Example Prediction
Input
نسخ التعليمات البرمجية
Text
تم الإعلان عن علاج نهائي للسرطان خلال يوم واحد
Prediction
نسخ التعليمات البرمجية
Text
Fake News
هيكل المشروع | Project Structure
نسخ التعليمات البرمجية
Text
Arabic_Fake_News_Detection
│
├── data
│   └── fake_news_dataset.csv
│
├── notebook
│   └── Arabic_Fake_News_Detection.ipynb
│
├── model
│   ├── fake_news_model.h5
│   ├── tokenizer.pkl
│   └── label_encoder.pkl
│
└── README.md
ا
##############################################################################################################
لتطوير المستقبلي | Future Improvements
English
Possible future improvements include:
Using Transformer models such as AraBERT
Increasing dataset size
Building a web application interface
Real-time news verification
العربية
يمكن تطوير المشروع مستقبلًا من خلال:
استخدام نماذج Transformer مثل AraBERT
زيادة حجم البيانات المستخدمة
إنشاء واجهة ويب للنظام
تحليل الأخبار في الوقت الحقيقي
المؤلف | Author
نسخ التعليمات البرمجية
Text
############################################################################################################
NLP Project - Fake News Detection
كلمات مفتاحية للمشروع | GitHub Tags
نسخ التعليمات البرمجية
Text
NLP
DeepLearning
FakeNewsDetection
ArabicNLP
LSTM
MachineLearning
TensorFlow
Python
