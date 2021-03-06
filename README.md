# The MEDFORD Language Specification

This repository hosts the language specification for the MEDFORD metadata language (Metadata Format for Open Reef Data).

## The MEDFORD implementation

The MEDFORD language is implemented by the `medford` parser; the current implementation is written in Python and hosted [here](https://github.com/TuftsBCB/medford).

## Example MEDFORD Files
A repository of sample MEDFORD files is hosted [here](https://github.com/TuftsBCB/MEDFORD-examples). (Note: Out of date/Not compatible with current spec as of 04/13/22. Will be updated soon.)

## MEDFORD Abstract
The conference publication about the alpha version of MEDFORD is hosted on Polina Shpilker's personal site, [here](https://www.eecs.tufts.edu/~pshpil01/MEDFORD_CCIS.pdf). The abstract is also copied below.

Reproducibility of research is essential for science. However, in the way modern computational biology research is done, it is easy to lose track of small, but extremely critical, details. Key details, such as the specific version of a software used or iteration of a genome can easily be lost in the shuffle, or perhaps not noted at all. Much work is being done on the database and storage side of things, ensuring that there exists a space to store experiment-specific details, but current mechanisms for recording details are cumbersome for scientists to use. We propose a new metadata description language, named MEDFORD, in which scientists can record [or encode!] all details relevant to their research. Human-readable, easily-editable, and templatable, MEDFORD serves as a collection point for all notes that a researcher could find relevant to their research, be it for internal use or for future replication. MEDFORD has been applied to coral research, documenting research from RNA-seq analyses to photo collectionsHuman-readible metadata file format to consolidate research information such that it can be stored, updated, and submitted to databases without introducing a huge time investment overhead.

## Contributions & Thanks
Contributors to the development of MEDFORD are as follows:
Polina Shpilker (polina.shpilker@tufts.edu), John Freeman, Hailey McKelvie, Jill Ashey, Jay-Miguel Fonticella, Hollie Putnam, Jane Greenberg, Lenore Cowen (cowen@cs.tufts.edu), Alva Couch (couch@cs.tufts.edu) and Noah M. Daniels (noah_daniels@uri.edu)

Please contact Polina, Lenore, Alva, or Noah with any questions.

Thank you to initial seed funding from: NSF grant OAC-1939263.