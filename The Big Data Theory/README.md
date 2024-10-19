# dataset description
Mixed dataset built for research purposes.

## Entries
* file1.ann: 44111  entries
* file2.ann:  18236 entries

## File Format
text - IOB2

| Column | Description       |
| ----- | ------------------ |
|token | a string feature |
|ner_tag| a classification label - 23 classes |

## Labels
<pre>
B-person
I-person
B-place
I-place
B-organization
I-organization
B-quantity
I-quantity
B-time
I-time
B-event
I-event
B-abstract
I-abstract
B-substance
I-substance
B-object
I-object
B-animal
I-animal
B-plant
I-plant
</pre>

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