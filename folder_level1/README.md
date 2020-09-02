# This is a README at folder level 1
---

In this folder there are two files and one additional folder

Again, linking is easy with all links being relative to the folder the current file is in so to link to README_2 I need to do `[link text](README_2.md)`, [like this](README_2.md). To link back up folders you use the usual `../`, [like this](../README.md).

## A way to have multilple READMEs in a folder
Github will by default only display the file named README.md when viewing a folder. If you want to have multiple documentation files within a folder (e.g. one to document each file) then the only way (I think) that you can do it is to have one base README.md and then use links to [other README files](README_2.md). It's not ideal but it will work. 

The other option which may work for public facing documentation would be [github wiki](https://guides.github.com/features/wikis/) but these are more for more established software projects that you expect other people to use a lot. 
