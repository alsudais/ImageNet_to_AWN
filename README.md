# ImageNet to Arabic WordNet 

This repository includes the datasets presented in *Alsudais A. Extending ImageNet to Arabic using Arabic WordNet. In: Proceedings of the First Workshop on Advances in Language and Vision Research. Online: Association for Computational Linguistics; 2020:1-6. doi:10.18653/v1/2020.alvr-1.1.*

![Images directly](https://github.com/alsudais/ImageNet_to_AWN/blob/master/ImageNet_to_AWN_direct.PNG )
![Images using hypernyms](https://github.com/alsudais/ImageNet_to_AWN/blob/master/ImageNet_to_AWN_hypernyms.PNG )



## Datasets 
### ImageNet_to_AWN.csv: 
Each ImageNet synset is presented in a row. The Arabic matches found directly and using hypernyms are in the columns. I used "0" for direct and "[]" for hypernyms when Arabic matches were not found 

### ImageNet_to_AWN_with_hypernyms_IDs.csv:
The same results but with the WordNet IDs for hypernyms. Cells with "0" indicate that an Arabic match was not available  

## Downloading the images: 
You can download the images from the official  [ImageNet website](http://image-net.org/download)

## Citation:
To cite this work:
```bibtex
@inproceedings{alsudais-2020-extending,
    title = "Extending {I}mage{N}et to {A}rabic using {A}rabic {W}ord{N}et",
    author = "Alsudais, Abdulkareem",
    booktitle = "Proceedings of the First Workshop on Advances in Language and Vision Research",
    month = jul,
    year = "2020",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2020.alvr-1.1",
    doi = "10.18653/v1/2020.alvr-1.1",
    pages = "1--6",
    abstract = "ImageNet has millions of images that are labeled with English WordNet synsets. This paper investigates the extension of ImageNet to Arabic using Arabic WordNet. The objective is to discover if Arabic synsets can be found for synsets used in ImageNet. The primary finding is the identification of Arabic synsets for 1,219 of the 21,841 synsets used in ImageNet, which represents 1.1 million images. By leveraging the parent-child structure of synsets in ImageNet, this dataset is extended to 10,462 synsets (and 7.1 million images) that have an Arabic label, which is either a match or a direct hypernym, and to 17,438 synsets (and 11 million images) when a hypernym of a hypernym is included. When all hypernyms for a node are considered, an Arabic synset is found for all but four synsets. This represents the major contribution of this work: a dataset of images that have Arabic labels for 99.9{\%} of the images in ImageNet.",
}
```
You can also download the [BibTex file here ](https://www.aclweb.org/anthology/2020.alvr-1.1.bib). You should also cite the original ImageNet paper and the Arabic WordNet papers. 

## Contact:
AAlsudais at outlook. 
