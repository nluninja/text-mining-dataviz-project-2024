# dataset description
The dataset contains text from Twitter, Stack Overflow responses, YouTube comments, and Reddit comments.


## Entries
* file1.ann: 62730 entries  
* file2.ann: 23394 entries 
* file3.ann: 15733 entries


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