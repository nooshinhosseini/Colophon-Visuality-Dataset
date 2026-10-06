This repository contains the research data and documentation produced for the project **“Colophons as Structured Visual Data,
Term Paper for the Course ‘Manuscripts from the Persianate and Islamic World: material and digital approaches’
”**

The project examines the visual organization of colophons in a bounded corpus of digitized manuscripts and explores how structured annotation can support comparison between characteristics that are often described separately in manuscript scholarship. Particular attention is given to relationships among the geometry of writing, framing, graphic treatment, and the organization of page space.

The dataset is intended as an exploratory research dataset rather than a comprehensive survey or definitive taxonomy of colophon forms.





## Dataset Scope

This analytical corpus consists of **39 manuscripts containing 49 individually annotated colophons**.

The digitazed manuscripts are held by the **University of Michigan** and were selected from catalogue records according to the following criteria:
- catalogue language: Persian or Turkish/Ottoman;
- date: before 1500 or between 1500 and 1599;
- availability of a digitized manuscript;
- identification of a colophon through examination of the digitized manuscript.

The corpus is deliberately bounded and should not be treated as representative of Persian or Ottoman manuscript production as a whole. Its composition is affected by the holdings of a single repository, digitization, and the information made discoverable through catalogue metadata.




## Repository Structure

├── README.md
├── data/
│   ├── manuscripts.csv
│   ├── colophons.csv
│   ├── languages.csv
│   ├── manuscript_languages.csv
│   └── colophon_languages.csv
└── documentation/
    ├── schema.sql
    └── codebook.csv
