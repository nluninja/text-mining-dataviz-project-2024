# Dataset description
This dataset consists of abstracts and full-text biomedical papers.

## Entries
* _file1.ann_: 71697 entries
* _file2.ann_:  45939 entries

## File Format
IOB2

| Column | Description        |
| ----- | ------------------ |
|id | a string feature. |
| start | begin character position |
| end chunk_tags| end character position|
|ner_tags| a list of classification labels|


|Labels|
| ------ |
|Anatomical_system 
|Cell
|Cellular_component
|Developing_anatomical_structure
|Immaterial_anatomical_entity
|Multi-tissue_structure
|Organ
|Organism_subdivision
|Organism_substance
|Pathological_formation
|Tissue


## Example
<pre>
Ventricular	0	11	B-Multi-tissue_structure
fibrillation	12	24	O
</pre>