Automated Ontology Generation for Zero-shot Defect Identification in Manufacturing

 Abstract:This paper establishes a methodology to automatically extract multi-
level attributes from literature to improve defect representation,
thereby facilitating ZSL. The extracted attributes contribute
to a hierarchical knowledge graph, called defect ontology, to
characterize multiple aspects of manufacturing defects. The
proposed algorithm takes the defect images and associated text
from the literature as input and develops an unsupervised method
to identify the hierarchical relationships among the tokenized
information extracted from the input text-feature corpora. The
hierarchical graph is refined to retain the most relevant informa-
tion by a pruning algorithm based on a minimum path search. A
walk algorithm, along with NLP, parsed the generated ontology to
create embedding of defects to enable zero-shot attribute learning
to identify defects. The proposed method advances the ZSL
methodology by automatically creating a hierarchical knowledge
representation from literature and images to replace generic
vocabulary in LLM adopted by ZSL algorithms, thus improving
defect representation. 

Note to Practitioners: This paper is among the earlier attempts to
integrate literature with data measured from real manufacturing
processes for diagnosis and certification. Traditionally, machine
learning requires extensive experiments to collect data, including
labeled data and associated process conditions, to character-
ize process-quality relationships, presenting entry barriers for
inexperienced manufacturing. This study proposes integrating
the automatic generation of defect ontology to enable defect
identification leveraging documented texts, such as published
journals or documents, based on limited measurement from
real processes. The methodology consists of a pipeline of three
algorithms, automated generation of hierarchical knowledge
