# Dataset description

The dataset contains tweets collected over stratified times, places and social uses. 

## Entries

* _file5.ann_: 34063 entries
* _file6.ann_: 29482 entries

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
