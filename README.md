# John Sherman  
## About me  

I am a Postdoctoral Scientist in the lab of Dr. Emily Theisen at the Center for Childhood Cancer Research at Nationwide Children's hospital in Columbus Ohio, USA. My current research involves determining the mechanism of action for the Lysine-specific Demethylase 1 (LSD1) inhibitor SP-2509 in Ewing Sarcoma. Over the course of this project, I have discovered that in addition to inhibiting LSD1, SP-2509 acts to inhibit the incorporation of iron sulfur clusters into nascent proteins, as well as gained experience working with high-performance computing and analyzing genomic and proteomic data.  
  
My undergraduate and graduate research experience focused on molecular and cellular biology with an emphasis on cell cycle regulation and metabolism. As an undergraduate I did research with Dr. David Rivers and Dr. Rebecca Brogan at Loyola University Baltimore on the expression of heat shock proteins during the development of flesh fly larvae. As a graduate student with Dr. Ruoning Wang at the Ohio State University, where my research focused on the integration of cell cycle control in G2 and metabolism. I gained a solid foundation in molecular biology and expertise in metabolic assays and flow cytometry especially concerning cell synchronization and the measuring of cell cycle progression. I developed a novel method to rapidly measure the progression of cells from G2 phase to mitosis. Approaching the end of my graduate career I taught myself the python programing language and the basics of data science. For my postdoctoral training, I am continuing to develop my abilities in data science and bioinformatics along those in molecular biology.   
<br>  
___
  
## Projects  

- Using the Rust programing language, I wrote a program to optimize parameters for a logarithmic curve to describe the data from a Cellular Thermal Shift Assay coupled with proteomic mass spectrometry (CETSA-MS). Available analytical programs at the time were made assumptions about the data that were too restrictive for our use case. While I initially created a solution using python, the non-linear data from our CETSA-MS required optimizing the initial guess for the parameters that we were estimating, and the python solution took several hours to run per an iteration. Using the rust interface for the Polars dataframe library and multithreading I was able to create a solution that ran quickly enough that we could optimize the initial guess in a reasonable amount of time. This allowed us to find a very interesting and unexpected result in data that would otherwise have been excluded from the analysis.  
  
- To further investigate whether SP-2509 or other iron disrupting compounds have potential to treat cancers beyond Ewing Sarcoma, I have been investigating the drug repurposing screens provided by DepMap. Similar to the evolving field of single cell transcriptomics, this is sparse data over many features and many observations that are not easily assigned to identifiable groups. Using emerging tools for use in single cell transcriptomics I hope to identify new biomarkers that can help identify cancers as promissing targets for repurposed drugs, as well as identify candidate drugs with unexpected secondary targets. 
<!--
**JShermanK1/JShermanK1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
