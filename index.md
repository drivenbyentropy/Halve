---
layout: home
---
# AptaSUITE <a href="https://github.com/drivenbyentropy/aptasuite/releases/latest/" title="posts" class="posts-menu-icon-zip"></a> <span class="download-zip">&#8681; BINARY</span> <a href="https://github.com/drivenbyentropy/aptasuite/releases/latest" title="posts" class="posts-menu-icon-source"></a> <span class="download-source">&#8681;&nbsp;SOURCE</span>

AptaSUITE is a platform independent implementation of multiple algorithms designed for the identification of aptamer candidate sequences and the analysis of the SELEX process per se. It provides both, command line and graphical user interfaces.

AptaSUITE is designed to be scalable with both data size and CPU count while minimizing the memory footprint by providing fast, off-heap data structures and storage solutions.

In its core, AptaSUITE consists of a collection of APIs and corresponding implementations facilitating storage, retrieval, and manipulation of aptamer data (such as sequences, aptamer counts in individual selection cycles, structure information and more). On top of these core data structures, a number of previously published algorithms have been implemented. Currently, these are [AptaPLEX](https://www.ncbi.nlm.nih.gov/pubmed/27080809), [AptaSIM](https://www.ncbi.nlm.nih.gov/pubmed/25870409), [AptaCLUSTER](https://www.ncbi.nlm.nih.gov/pubmed/25558474), and [AptaTRACE](https://www.ncbi.nlm.nih.gov/pubmed/27467247).

<br><br><a href="{{ site.url }}/images/architechtureweb2.png"><img src="{{ site.url }}/images/architechtureweb2.png" alt="AptaSuite Libraries"></a>  

<center> The programmatic architecture of <b>AptaSuite</b>. Core libraries for the storage, retrieval and manipulation of aptamers are accessed through a well-defined API which in turn serves data to and accepts data from the algorithms responsible for input, processing, and output of aptamers. Each computational method is accessible either from command line or through the graphical user interface. </center><br>

### Installation and Usage

Download the latest precompiled version from the [release page](https://github.com/drivenbyentropy/aptasuite/releases) <b>or</b> [build the project from source](https://github.com/drivenbyentropy/aptasuite/wiki/Compiling-from-source). 
```bash
git clone https://github.com/drivenbyentropy/aptasuite.git
mvn install
```

A detailed manual is available through the [Wiki](https://github.com/drivenbyentropy/aptasuite/wiki) pages.

### Issues and Comments
If you have any issues or recommendations, please feel free to open a [ticket](https://github.com/drivenbyentropy/aptasuite/issues).

### Screenshots

{% capture images %}
	{{ site.url }}/images/screnshot2.png
	{{ site.url }}/images/screnshot4.png
	{{ site.url }}/images/screnshot1.png
	{{ site.url }}/images/screnshot3.png
{% endcapture %}
{% include gallery images=images caption="Screen shots of the Graphical User Interface implemented within AptaSUITE" cols=2 %}

### How to Cite
If you use AptaSuite in your work, please cite it as
```
AptaSUITE: A Full-Featured Bioinformatics Framework for the Comprehensive Analysis of Aptamers from HT-SELEX Experiments. 
Hoinka, J., Backofen, R. and Przytycka, T. M. (2018). 
Molecular Therapy - Nucleic Acids, 11, 515–517. https://doi.org/10.1016/j.omtn.2018.04.006
```
I addition, please cite the individual algorithms that aided your analysis. Details on how to cite these can be found in the `Help -> How to Cite` menu of the graphical user interface.

AptaSUITE is developed and maintained by Jan Hoinka from the [AlogCSB lab](https://www.ncbi.nlm.nih.gov/CBBresearch/Przytycka/index.cgi#research) at the Computational Biology Branch of the National Center for Biotechnology Information / National Library of Medicine, and is released under the GNU Public License (GPL 3.0). We are also grateful for significant ideas and code from Phoung Dao, Rolf Backofen, Teresa Przytycka, and other generous contributors.
