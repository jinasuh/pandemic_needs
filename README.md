# Supplementary Materials for Study on Human Needs during the COVID-19 Pandemic
This repository contains supplementary materials for research studies related to how human needs shift during the COVID-19 pandemic. 

For more information on this research project, please refer to our paper at https://arxiv.org/abs/2008.07045

## Human Needs Detection
`./needs_detection/needs_regex_full.tsv` contains a list of regular expressions used to extract human needs from search interactions. For definitions of need categories, please refer to the paper above.

- **Need Id**: maps to need subcategories
- **Logic**: KD refers to keyword and domain matching, Q refers to keyword only matching, D refers to domain only matching
- **QueryRegex**: Regular expression used to match the query string
- **DomainRegex**: Regular expressed used to match the clicked url 
