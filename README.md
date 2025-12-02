# NLI dataset for Japanese comparatives
This repository contains dataset for our paper.

Yosuke Mikami, Daiki Matsuoka, and Hitomi Yanaka. 2025. Can Large Language Models Robustly Perform Natural Language Inference for Japanese Comparatives?. In Proceedings of the 16th International Conference on Computational Semantics, pages 127–136, Düsseldorf, Germany. Association for Computational Linguistics.
## About the dataset
This dataset is constructed based on [Japanese semantic test suite (JSeM)](https://github.com/DaisukeBekki/JSeM).

### Data example
```json
{
    "id": "jsem_569_1",
    "category": [
        "basic_comparative"
    ],
    "premises": [
        "太郎は花子より明るい。",
        "花子は明るい。"
    ],
    "hypothesis": "太郎は明るい。",
    "answer": "yes"
}
```
* `id`: `jsem_569` is the ID of the original problem in JSeM.
* `category`: Each problem has at least one category.

## Citation
Yosuke Mikami, Daiki Matsuoka, and Hitomi Yanaka. 2025. Can Large Language Models Robustly Perform Natural Language Inference for Japanese Comparatives?. In Proceedings of the 16th International Conference on Computational Semantics, pages 127–136, Düsseldorf, Germany. Association for Computational Linguistics.
```
@inproceedings{mikami-etal-2025-large,
    title = "Can Large Language Models Robustly Perform Natural Language Inference for {J}apanese Comparatives?",
    author = "Mikami, Yosuke  and
      Matsuoka, Daiki  and
      Yanaka, Hitomi",
    editor = "Evang, Kilian  and
      Kallmeyer, Laura  and
      Pogodalla, Sylvain",
    booktitle = "Proceedings of the 16th International Conference on Computational Semantics",
    month = sep,
    year = "2025",
    address = {D{\"u}sseldorf, Germany},
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.iwcs-main.12/",
    pages = "127--136",
    ISBN = "979-8-89176-316-6"
}
```