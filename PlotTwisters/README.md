# Dataset description

the dataset contains DBPedia manually annotated collection of texts.

## Entries

* _file1.ann_: 1428 entries


## Format

| Column | Description       |
| ----- | ------------------ |
|token | a string feature |
|ner_tag| a classification label, |


| Label |
| ------ |
| LOC
| PER
| ORG
| MISC


## Example
<pre>
middle	O
aged	O
man	O
band	O
playing	O
blink	B-ORG
182	I-ORG
.	I-ORG
l0	O
l	O
.	O
. O
</pre>



