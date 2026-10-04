[Named_Entity_Recognition_README.md](https://github.com/user-attachments/files/33029661/Named_Entity_Recognition_README.md)
# named-entity-recognition-tea# Named Entity Recognition Application

A Python-based NLP application that identifies and categorizes important entities such as people, organizations, locations, and dates from unstructured text.

## Objective

The objective of this project is to automatically extract meaningful real-world entities from written text.

## Features

- Detects people
- Detects organizations
- Detects locations
- Detects dates
- Detects products and events
- Displays entity categories
- Generates entity statistics
- Visualizes entity distribution

## Technologies Used

- Python
- spaCy
- Pandas
- Matplotlib

## NLP Technique

The project uses **Named Entity Recognition (NER)** through the spaCy NLP library.

Common entity types include:

| Label | Meaning |
|---|---|
| PERSON | Person |
| ORG | Organization |
| GPE | Country, city, or state |
| LOC | Location |
| DATE | Date |
| MONEY | Monetary value |
| PRODUCT | Product |
| EVENT | Event |

## How It Works

1. User enters a paragraph.
2. spaCy processes the text.
3. The NLP model identifies entities.
4. Each entity receives a category.
5. The entities are displayed.
6. A distribution chart shows the detected entity types.

## Example

**Input:**

```text
Elon Musk founded SpaceX in California.
Microsoft announced a new AI project in Seattle in 2025.
```

**Output:**

```text
Elon Musk -> PERSON
SpaceX -> ORG
California -> GPE
Microsoft -> ORG
Seattle -> GPE
2025 -> DATE
```

## Requirements

```bash
pip install spacy pandas matplotlib
python -m spacy download en_core_web_sm
```

## Running the Project

Open `Named_Entity_Recognition.ipynb` in Google Colab, Jupyter Notebook, or VS Code.

Run the installation cell before loading the spaCy model.

## Project Structure

```text
Named-Entity-Recognition/
│
├── Named_Entity_Recognition.ipynb
└── README.md
```

## Applications

- News analysis
- Information extraction
- Document indexing
- Search engines
- Resume analysis
- Knowledge graph construction

## Conclusion

This project demonstrates how NLP can transform unstructured text into structured information by identifying important named entities.
