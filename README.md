A Program for Aligning Sentences in Bilingual Corpora
===========================================

## Introduction
The Gale – Church algorithm is a method in computational linguistics. It is for aligning corresponding sentences in a parallel corpus. [1](#ref) “A parallel text is a text placed alongside its translation or translations. Parallel text alignment is the identification of the corresponding sentences in both halves of the parallel text." [2](ref) Actually, the task is to align sentences to its corresponding translation.

The goal in gale-church paper [3](ref), is aligning sentences in one language to another language sentences. Therefore, the goal is to identify correspondences between sentences in one language and sentences in the other language. In this paper, they described a method and a program (align) to align sentences
based on a simple statistical (probabilistic) model of character lengths. The input is a pair of texts. For example, an English text and a French text. The output identifies the alignment between sentences of English text and French text.

## Data
I found a useful link for data in gitub. [4](ref) Liling tan has published some data in google drive. [5](ref) There are a lot of folders, however the last one
was useful for me. The name of the last file is: “NTU-MCv4.1-08Apr2013.tar.gz" In the subcorpora folder which is inside of the last file, we can find some datasets that are useful for different alignments. In this project, we want to have alignments by considering two documents. Therefore we should use the datasets that are inside the “doc_aligned" folder. In this project, I used Korean, English and Japanese documents.

## Result
Here are the results that I got for different corpora:


## <a name = "ref"/> References

1 https://en.wikipedia.org/wiki/Gale%E2%80%93Church_alignment_algorithm

2 https://en.wikipedia.org/wiki/Parallel_text

3 https://www.aclweb.org/anthology/J93-1004.pdf

4 https://github.com/alvations/NTU-MC

5 https://drive.google.com/drive/folders/1ResffV1GXLCK6Dc-0ZxFeBRS9CtnMS71


