# pdf_table_parser

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4587765.svg)](https://doi.org/10.5281/zenodo.4587765) [![Generic badge](https://img.shields.io/badge/Python-3.7-<red>.svg)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/License-MIT-purple.svg)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/Maintained-Yes-green.svg)](https://shields.io/) [![Generic badge](https://img.shields.io/badge/BuildPassing-Yes-red.svg)](https://shields.io/)

---

This is an extension of [pdfminer3k](https://pypi.org/project/pdfminer3k/), joint work with [ianknowles](https://github.com/ianknowles/pdftableparser) that extracts tabular data (with a focus on institutional accounts) from pdf files published under David Cameron's [2010 transparency push](https://webarchive.nationalarchives.gov.uk/20130104174825/http://www.number10.gov.uk/news/letter-to-government-departments-on-opening-up-data/).

Requires pdfminer3k and Pillow packages as detailed in the requirements.txt file (`pip install -r requirements.txt`)·

Outputs .csv files in the same directory as the input (.pdf) file. There might be the odd edge case; feel free to fork, unit test, and raise issues!

Funded by the British Academy as part of the [NHSSpend](https://github.com/crahal/NHSSpend) project. 
