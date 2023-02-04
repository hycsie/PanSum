# PanSum
This repo is for The Web Conf 2023 Poster.

This is the repo for The Web Conf 2023 Poster paper "Intent-based Web Page Summarization with Structure-Aware Chunking and Generative Language Models".
The "PanSum" dataset is prepared in similar to SQuAD format.

- The first layer is a dictionary of web pages with filename as key.
- The second layer is a list of chunks. For each chunk, "context" is a string that stores the content of chunk, while "qas"  is a dictionary that stores the annotation of each intent.
- In qas layer, the key is
