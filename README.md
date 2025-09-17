# NLI dataset for Japanese comparatives
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