# Open-ViTabQA: A Novel Benchmark for Vietnamese Question Answering on Open Domains Wikipedia Table

Open-ViTabQA is the first publicly available dataset for Vietnamese Table Question Answering (TQA). It is designed to benchmark the performance of language models, particularly Large Language Models (LLMs), on understanding and answering questions posed on Vietnamese Wikipedia tables.

## Motivation and Background

Tabular data is a rich source of information, and automated information extraction from tables is a crucial task in Natural Language Processing (NLP).  However, existing TQA resources are predominantly in English, with limited availability for low-resource languages like Vietnamese.  Vietnamese TQA presents unique challenges due to the language's complex word segmentation, diverse syntactic structures, and the prevalence of implicit information, making it difficult to directly apply models trained on English TQA datasets. Open-ViTabQA addresses this gap by providing a benchmark dataset for evaluating and advancing Vietnamese TQA research.

## Data Structure

Each instance in Open-ViTabQA consists of:

QAs data
| Field        | Description                                   |
|--------------|-----------------------------------------------|
| `qa_id`      | Unique identifier for the qa pair             |
| `table_id`   | Unique identifier for the table               |
| `question`   | Question                                      |
| `answer`     | Answer                                        |
| `hints`      | List of question type                         |

Tables data
| Field        | Description                                   |
|--------------|-----------------------------------------------|
| `table_id`   | Unique identifier for the table               |
| `table_html` | Table data in HTML format                     |
| `table_title`| Title of table                                |
| `table_domain`| Domain of table                              |
| `table_type` | List of types (normal|contain_merged_header|contain_merged_value)                              |
| `table_dict` | Flattened table (List of table rows) |



## Citation

To be added after paper acceptance

## Contact
If you have any further questions, please contact us at the following email:
21521972@gm.uit.edu.vn
