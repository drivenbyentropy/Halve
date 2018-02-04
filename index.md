---
layout: home
---
# AptaSUITE

<a href="https://github.com/drivenbyentropy/aptasuite/releases/download/v0.5/aptasuite-0.5.0.zip" title="posts" class="posts-menu-icon-zip"></a>
<span class="download-zip">&#8681; *.ZIP</span>
<a href="https://github.com/drivenbyentropy/aptasuite/releases/download/v0.5/aptasuite-0.5.0.zip" title="posts" class="posts-menu-icon-source"></a>
<span class="download-source">&#8681; *.TAR.GZ</span>

AptaSUITE is a platform independent implementation of multiple algorithms designed for the identification of aptamer candidate sequences and the analysis of the SELEX process per se.

AptaSUITE is designed to be scalable with both data size and CPU count while minimizing the memory footprint by providing fast, off-heap data structures and storage solutions.

In its core, AptaSUITE consists of a collection of APIs and corresponding implementations facilitating storage, retrieval, and manipulation of aptamer data (such as sequences, aptamer counts in individual selection cycles, structure information and more). On top of these core data structures, a number of previously published algorithms have been implemented. Currently, these are [AptaPLEX](https://www.ncbi.nlm.nih.gov/pubmed/27080809), [AptaSIM](https://www.ncbi.nlm.nih.gov/pubmed/25870409), [AptaCLUSTER](https://www.ncbi.nlm.nih.gov/pubmed/25558474), and [AptaTRACE](https://www.ncbi.nlm.nih.gov/pubmed/27467247).

<br><br><a href="{{ site.url }}/images/architechtureweb.png"><img src="{{ site.url }}/images/architechtureweb.png" alt="AptaSuite Libraries"></a>  

<center> The programmatic architecture of <b>AptaSuite</b>. Core libraries for the storage, retrieval and manipulation of aptamers are accessed through a well-defined API which in turn serves data to and accepts data from the algorithms responsible for input, processing, and output of aptamers. Each computational method is accessible either from command line or through the graphical user interface. </center><br>

# Installation

Download the latest precompiled version from the [release page](https://github.com/drivenbyentropy/aptasuite/releases) or [build the project from source](https://github.com/drivenbyentropy/aptasuite/wiki/Compiling-from-source).

# Usage

Please see the [Wiki](https://github.com/drivenbyentropy/aptasuite/wiki) for a detailed manual.

# Issues and Comments
If you have any issues or recommendations, please feel free to open a [ticket](https://github.com/drivenbyentropy/aptasuite/issues).
