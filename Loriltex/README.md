# dataset description
This dataset focuses on entity and relationship extraction relevant to somebody operating in the role of a defence and security intelligence analyst;The dataset comprised task-specific documents focused on the topic of the conflict in Syria and Iraq.

## Entries
* file1.ann: 19787  entries
* file2.ann:  5501 entries

## File Format
IOB2

| Column | Description       |
| ----- | ------------------ |
|token | a string feature |
|ner_tag| a classification label |

## Labels
|-------------------|
|DocumentReference
|Location
|MilitaryPlatform
|Money
|Nationality
|Organisation
|Person
|Quantity
|Temporal
|Weapon

## Example
<pre>
The	O
last	O
meeting	O
of	O
the	B-Organisation
Small	I-Organisation
Group	I-Organisation
took	O
place	O
in	O
Washington	B-Location
,	I-Location
D	I-Location
.	I-Location
C	I-Location
.	I-Location
</pre>
