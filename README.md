## 📁 Project Structure

```
Resume_parser/
│
├── README.md                      # Project documentation
├── Resume_parser_final.ipynb      # Main notebook for development and experimentation
│
├── base_config.cfg                # Base configuration for NLP model
├── config.cfg                     # Final training configuration file
│
├── jz_skill_patterns.jsonl        # Custom skill patterns for entity recognition
├── train_data.pk                  # Serialized training dataset
├── train_new.spacy                # Trained spaCy model data
```

---

## 📂 File Descriptions

### 📘 README.md

Contains project overview, setup instructions, and usage guide.

### 📓 Resume_parser_final.ipynb

Jupyter Notebook used for:

* Data preprocessing
* Model training
* Testing and evaluation

### ⚙️ base_config.cfg

Initial configuration file used to define the NLP pipeline structure before training.

### ⚙️ config.cfg

Final configuration file used for training the spaCy model with optimized parameters.

### 🧠 jz_skill_patterns.jsonl

Contains predefined skill patterns used for:

* Named Entity Recognition (NER)
* Skill extraction from resumes

### 📦 train_data.pk

Pickle file containing the processed training dataset.

### 🤖 train_new.spacy

Trained spaCy model file used for:

* Extracting entities
* Running inference on resumes

---

## 📝 Notes

* The project uses **spaCy** for building and training the NLP model
* Custom NER is implemented for better skill extraction
* Training data can be extended to improve model accuracy
