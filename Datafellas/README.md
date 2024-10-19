# Dataset description
The dataset is generated using financial documents obtained from U.S. Security and Exchange Commission filings.

## Entries
* file2.ann: 41010 entries
* file1.ann:  13246 entries


## File Format
IOB2 

| Column | Description        |
| ----- | ------------------ |
|id | a string feature. |
| chunk label | a classification label for named entity |
| - | empty column|
|ner_tags| a classification label for named entity|


## Labels
| ------ |
|PER
|LOC
|ORG
|MISC

## Example
<pre>
-DOCSTART- -X- O O

Subordinated NNP - O
Loan NNP - O
Agreement NNP - O
- : - O
Silicium NNP - I-ORG
</pre>