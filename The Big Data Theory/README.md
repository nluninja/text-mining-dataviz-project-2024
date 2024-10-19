# Dataset description
Mixed dataset built for research purposes.

## Entries
* _file1.ann_: 44111  entries
* _file2.ann_:  18236 entries

## File Format
IOB2

| Column | Description       |
| ----- | ------------------ |
|token | a string feature |
|ner_tag| a classification label - 23 classes |

| Labels |
| -------- |
| person
| place
| organization
| quantity
| time
| event
| abstract
|substance
| object
| animal
| plant


## Example
<pre>
    Pacific	B-person
    Standard	I-person
    owner	I-person
    ,	O
    Jonathan	B-person
    M.	I-person
    Stan	I-person
    ,	O
    displays	O
    the	O
    Santorum	B-substance
    cocktail	I-substance
    drink	I-substance
    as	O
    a	B-object
    finished	I-object
    product	I-object
</pre>