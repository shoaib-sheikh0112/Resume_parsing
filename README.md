# Resume_parsing
Made a resume parser using Spacy NPL. Firstly extracted text from around 800 resumes which were in pdf and docx form. After that cleaned that text, After cleaning did data annotation using doccano.
When our data annotion was done started traing a NER model using spaCy NLP. Entities on which our model was trained are Name, Designation, Companies worked at, Skills, College, Email, Location.
Trained model on 80% data and saved 20% data for model testing. After testing Model added a OCR for real life use of that trained model
Added OCR so that it can convert pdf/docx into text and then the trained model can work on that text data to extract entities.
