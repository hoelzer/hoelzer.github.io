---
title: "Decoding bacterial methylomes in four public health-relevant microbial species: nanopore sequencing enables reproducible analysis of DNA modifications"
date: 2025-04-23
publishDate: 2025-04-23
authors: ["Valentina Galeone", "Johanna Dabernig-Heinz", "Mara Lohde", "Christian Brandt", "Christian Kohler", "Gabriel E. Wagner", "**Martin Hölzer**"]
publication_types: ["2"]
abstract: "Investigating bacterial methylation profiles provides essential complementary information to the native DNA sequence, significantly extending our understanding of how DNA modifications influence virulence, antibiotic resistance, and the ability of bacteria to evade the immune system. Recent advancements in real-time Nanopore sequencing and basecalling algorithms have enabled the direct detection of modified bases from raw signal data, eliminating the need for bisulfite treatment of DNA. However, decoding methylation signals remains challenging due to rapid technological and methodological progress. In this study, we focus on public health-relevant bacterial strains to analyze their methylation profiles and identify methylation motifs. Our dataset includes samples from Staphylococcus aureus, Listeria monocytogenes, Enterococcus faecium, and Klebsiella pneumoniae, sequenced on the Nanopore GridION platform using the latest flow cell chemistry (R10.4.1) and modification basecalling models (Dorado basecalling SUP model v5). We investigated distinct methylation patterns within and between species, focusing on heavily modified genes or genomic regions. Our results reveal distinct species-specific methylation profiles, with each strain exhibiting unique modification patterns. We developed a modular pipeline using Nextflow and the Nanopore Modkit tool to streamline the detection of methylated motifs. We compared the results with outputs from MicrobeMod, a recent toolkit for exploring prokaryotic methylation and base modifications in nanopore sequencing. Our pipeline is publicly available for further use (github.com/rki-mf1/ont-methylation). We identified known methylation motifs already described in the literature and novel de novo motifs, providing deeper insights into the diversity of bacterial DNA modifications. Furthermore, we identified genomic regions that are extensively methylated, which could have implications for bacterial behavior and pathogenicity. We also assess improvements in basecalling accuracy, specifically how methylated bases can influence neighboring basecalls. Recent advances in basecalling models, particularly v5 models as part of Dorado, have reduced these issues, improving the reliability of methylation detection in bacterial genomes. In conclusion, our study highlights the potential of current nanopore sequencing tools for detecting DNA modifications in prokaryotes. By making our pipeline and results publicly available, we facilitate further research into bacterial DNA modifications and their role in microbial pathogenesis."
featured: true
publication: "BMC Genomics, 26 (394)"
links:
  - icon_pack: fas
    icon: scroll
    name: Link
    url: 'https://link.springer.com/article/10.1186/s12864-025-11592-z'
  - icon_pack: fab
    icon: github
    name: Code 
    url: 'https://github.com/rki-mf1/ont-methylation'
  - icon_pack: ai
    icon: open-data
    name: Open Data
    url: 'https://doi.org/10.17605/OSF.IO/JFY75'

---

