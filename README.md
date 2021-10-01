# standards-gpf
Global Proficiency Framework for Reading and Mathematics.

Jurisdiction info
-----------------
The Global Proficiency Framework (GPF) for Mathematics and Reading were developed
by the UNESCO Institute of Statistics (UIS);
US Agency for International Development (USAID); the World Bank;
Development Office (FCDO)—formerly the UK Department for International Development (DFID);
the Australian Council for Educational; and Foreign, Commonwealth and Research (ACER);
the Bill and Melinda Gates Foundation;
and representatives of many other development partner organizations.
 
A team of more than 60 reading and math subject matter experts (SMEs) from around the globe,
all of whom have experience working in multiple countries and contexts, came together to create the GPF.
The GPF defines, for primary school reading and mathematics, the global minimum proficiency level
that learners are expected to demonstrate at the end of each grade (one through nine).
The SMEs reached consensus on the statements of knowledge and/or skill(s) (sometimes called content standards)
and the global performance descriptors (GPDs) (sometimes called performance standards)
described in the GPF based on their knowledge of developmental progressions and the UIS’s Global Content Framework,
which was based on:
- 73 curriculum and assessment frameworks from 25 countries for reading and
- 115 assessment frameworks from 53 countries for mathematics.



Contents
--------
- [`sourcedocuments/`](./sourcedocuments): source documents (PDFs)
  - `Global-Proficiency-Framework-Mathematics.pdf`: GPF for Mathematics
    - `GPF_math_table.pdf`: PDF table that contains the data to be digitized
  - `Global-Proficiency-Framework-Reading.pdf`: GPF for Reading
    - `GPF_reading_table.pdf`: PDF table that contains the data to be digitized
- [`sourcedata/`](./sourcedata): machine-readable source documents (spreadsheets)
- [`terms/`](./terms): controlled vocabularies used in the digitized standards:
  - [`CurriculumElements.yml`](./terms/CurriculumElements.yml): terms describing
    the different "types" of elements within the curriculum standards
  - [`Subjects.yml`](./terms/Subjects.yml): terms for the academic subjects within the jurisdiction
  - [`GradeLevels.yml`](./terms/GradeLevels.yml): localized grade levels
- [`standards/`](./standards): curriculum standards ROCdata


Digitization notes
------------------
- Text from the source documents was extracted using `pdftotext` and manually
  edited and restructured to create the machine-readable format files in `sourcedata/`



License
-------
All documents and data in this repo are under copyright © UNESCO Institute of Statistics (UIS) and partners.
The digital representations of terms and standards data in this repository are
for illustrative purposes part of the [ROC data project](https://rocdata.global/)
and should not be considered endorsed or approved by the UIS in any way.

