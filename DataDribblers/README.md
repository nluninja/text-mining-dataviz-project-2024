# Dataset description
The dataset contains text from Twitter, Stack Overflow responses, YouTube comments, and Reddit comments.

## Entries
* _file1.ann_: 62730 entries  
* _file2.ann_: 23394 entries
* _file3.ann_: 15733 entries

## File Format
IOB2

| Column | Description        |
| ----- | ------------------ |
|id | a string feature. |
|ner_tags| a list of classification labels|

| Labels |
| ------ |
| person
| location
| group
| corporation
| product
| creative-work

## Example
<pre>
From	O
Green	O
Newsfeed	O
:	O
AHFA	B-group
extends	O
deadline	O
</pre>