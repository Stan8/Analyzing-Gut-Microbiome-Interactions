# BLAH8-Biomedical-Relation-Annotation
<p style="text-align:justify;">
Harnessing the potential of the latest information retrieval techniques relies highly on annotated corpora. In this project, we intend to introduce a corpus gathering different concepts strongly correlated with the human gut microbiome, along with the relations among them. The selected corpora consists of full text articles, separated into paragraphs or sentences, provided by PubTator along with their named entities annotations. These includes 6 concepts: Gene, Disease, Cell Line, Species, Mutation and Chemical. Each paragraph represents a unit of meaning, implying that the relation may be expressed anywhere within the unit (in the same sentence as the named entities, or across the other sentences). The interaction types between pairwise entities are partly derived from the UMLS Semantic Network. There are 22 relations describing interactions that occur between the previsouly mentioned entity types, and they are defined as follows: Increase, Decrease, Stop, Start, Improve, Worsen, Possible, Presence, Negative_correlation, Affects, Causes, Complicates, Experiences, Interacts_with, Location_of, Marker/Mechanism, Prevents, Reveals, Treats, Physically_related_to, Part_of, Associated_with.
</p>


## Annotating the dataset
<p style="text-align:justify;">
Emerging Large Language Models have shown to be efficient and accurate for multiple tasks, raising the question of their use in annotation use cases, as the labeling process can be costly, especially in domains of speciality. Our annotation process of relations is designed in two distinct phases. In the initial phase, annotators will be tasked with evaluating and confirming or refuting the anticipated relationship between two entities. These predictions will be generated externally utilizing a Language Model (LLM). Following this, in the second phase, annotators will take an active role in choosing the appropriate annotation, with the option of leveraging ChatGPT for assistance. This means that the annotator will have to choose one of the previsouly mentioned interaction types. The overarching objective of this methodology is to scrutinize and quantify the impact of each annotation process setting, as the inter-annotator agreement will be calculated for each setting, offering invaluable insights for the automation of biomedical annotations.
To sum up, the aim of this project is to:
* Evaluate LLM predictions of relations;
* Annotate relations linking entities, by choosing the interaction type, using external knowledge if needed. 
</p>

