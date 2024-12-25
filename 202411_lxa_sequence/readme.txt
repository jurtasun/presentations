## Introduction to probability & statistical inference *Ovis aries*

### Dr. Jesús Urtasun Elizari LMS & ICLI
### Dr. Josemari Urtasun Elizari VUA

<img src="/readme_figures/grad-school-logo.png">

### Find the content of the course in GitHub:
[https://github.com/jurtasun/probability_stats_intro](https://github.com/jurtasun/probability_stats_intro)

This course provides an introduction to the field of probability and statistical inference.
The topics covered will include basic concepts on probability theory, inference, distributions, and hypothesis testing. 
The aim of the course is to provide strong foundations at the mathematical and theoretical level, while providing practical exercises to work on real data.

The course is organized in three chapters, covering topics listed below. 
All will be followed by a practical session and hands-on coding, both in Python and R.
No prior experience on statistics or programming is required for the attendance of this course.

## Roadmap of the course

### Chapter 1. Introduction to probability & random events.

https://www.darwintreeoflife.org
/opt/resources/genomes/Homo_sapiens/GRCh38/sequence

Experimental process ..................................................................................................

1. Sample Collection and DNA Extraction
Select individuals: Choose a few representative Oveja Lacha individuals to obtain high-quality DNA that reflects the genetic diversity of the breed.
Collect samples: Obtain tissue or blood samples and ensure they are fresh or well-preserved to avoid DNA degradation.
DNA extraction: Use a high-quality DNA extraction method to obtain high-molecular-weight DNA, which is essential for long-read sequencing.

2. Sequencing Strategy
Short-Read Sequencing: Illumina technology is commonly used for short-read sequencing due to its high accuracy and coverage. 
These reads are useful for detecting small variants and assembling the core sequence.
Long-Read Sequencing: Use a long-read sequencing platform like PacBio or Oxford Nanopore to help assemble repetitive regions, structural variants, 
and complex regions. Long reads are essential for building a contiguous, high-quality genome assembly.
Hi-C or Optical Mapping (optional but recommended): Use Hi-C or optical mapping techniques to scaffold contigs and improve genome assembly quality. 
This helps with the arrangement of contigs into chromosomal-level scaffolds, producing a more complete reference.

3. Genome Assembly
Assemble short and long reads: Use a genome assembler that can incorporate both long and short reads, 
such as Canu, Flye (for long-read assembly), or SPAdes (for hybrid assembly). This will generate initial contigs or scaffolds.
Polish the assembly: Use the short-read data to correct errors in the long-read assembly, using tools like Pilon or NextPolish.
Scaffolding: Integrate Hi-C or optical mapping data to order and orient the contigs into chromosomal scaffolds, giving a more complete assembly.

4. Annotation
Gene Prediction: Use automated annotation pipelines like MAKER or Augustus to predict genes, coding regions, and other functional elements in the genome.
Functional Annotation: Map known sheep proteins or use de novo annotation to assign potential functions to predicted genes.

5. Quality Assessment
Evaluate assembly quality: Check genome completeness with BUSCO (Benchmarking Universal Single-Copy Orthologs) 
to ensure that essential genes are present and assess coverage and accuracy.
Assess contiguity: Metrics like N50 and L50 can help evaluate the continuity and quality of the assembled genome.

6. Create a Publicly Available Reference
Submit the final assembled and annotated genome to a public database, such as NCBI GenBank or ENSEMBL, making it available as a reference genome for Oveja Lacha.
By following these steps, you should be able to generate a high-quality reference genome for Oveja Lacha.

Permissions and legislation ...........................................................................................

1. Animal Use and Ethical Approval
Ethics Committee Approval: Contact an accredited Animal Experimentation Ethics Committee (CEEA in Spanish). 
This approval is required if the work involves sample collection from animals.
Animal Care and Use Authorization: If you’re affiliated with an institution, this will likely be processed internally. 
Independent researchers may need to approach a local institution or seek advice from CEEAs that accept external applications.

2. Sample Collection Permits
Owner Permission: Get written consent from the sheep’s owner to collect tissue or blood samples.
Protected Species Consideration: Since Oveja Lacha is a local breed, 
you’ll need to verify if it has any special protections under Spanish or European Union biodiversity regulations.

3. Genetic Resources Access Compliance
Nagoya Protocol: Although Spain follows the Nagoya Protocol, which regulates access to genetic resources, 
for local breeds like Oveja Lacha, you may not need additional permissions if the work remains academic and non-commercial. 
If there’s any commercial intention, you’ll need to register and ensure compliance with benefit-sharing obligations.
Spanish National Biodiversity Strategy: Check with Spain’s Ministry for the Ecological Transition (MITECO)
for any biodiversity or genetic resource regulations that might affect your project.

4. Data Sharing and IP Considerations
Data Repository Requirements: If publishing or sharing the genome in a public repository, follow the repository's guidelines. 
GenBank and ENSEMBL require specific metadata, including proof of ethical compliance and permissions for data submission.
Intellectual Property: If you foresee any commercial use, consult with a legal expert to understand 
Spain's intellectual property laws regarding genetic data and biodiversity.

Cost estimation .......................................................................................................

1. Sample Collection and DNA Extraction
Sample Collection: Assuming you’ll be collecting blood or tissue samples yourself with the farmer’s permission, 
costs might include basic consumables (e.g., syringes, tubes, transport media). Costs could be:
€50 - €100 (assuming simple sample collection).
DNA Extraction and Quality Control: High-quality DNA extraction for sequencing can cost about:
€100 - €300 per sample if outsourced to a university lab, depending on the lab’s pricing and the quality of DNA needed.
Estimated Total for Sample Collection & Extraction: €150 - €400

2. Sequencing Costs
Short-Read Sequencing (Illumina): High coverage (~50-100x) is required to get sufficient data for polishing and error correction. 
Using Illumina’s NovaSeq or NextSeq platform, this typically costs:
€2,000 - €4,000 depending on the exact platform and coverage level.
Long-Read Sequencing (PacBio or Oxford Nanopore): Long-read sequencing is essential for assembling repetitive regions. 
PacBio is more accurate but expensive; Oxford Nanopore is often more cost-effective but may be less accurate.
PacBio: ~€5,000 - €8,000 for sufficient coverage (~30-50x).
Oxford Nanopore: ~€2,000 - €4,000 for similar coverage.
Optional - Hi-C or Optical Mapping: If you aim for chromosome-level assembly, Hi-C or optical mapping can improve scaffold accuracy, costing about:
€2,000 - €5,000.
Estimated Total for Sequencing: €6,000 - €15,000

3. Bioinformatics and Data Analysis
Genome Assembly and Polishing: Software tools are usually free or open-source, but high-performance computing (HPC) resources are required. If the university has HPC resources, these might be available for free or at a reduced cost. Commercial services could range between:
€1,000 - €3,000 for complete assembly and initial annotation if outsourced.
Annotation and Functional Analysis: Annotation pipelines, if run on institutional servers, might not add extra cost, but you might need technical assistance.
€500 - €2,000 if outsourced.
Estimated Total for Bioinformatics: €1,500 - €5,000

4. Legal and Regulatory Fees
Ethics Approval: University ethics boards may not charge, but if you need external approval, expect potential processing fees.
Nagoya Protocol Compliance: If you’re conducting non-commercial research within Spain, there’s likely no fee, but confirm with MITECO to avoid compliance issues.
Estimated Total for Legal/Regulatory Fees: €0 - €500.
5. Miscellaneous and Contingencies
Plan for about 10% of the budget to cover unexpected costs (e.g., repeat sequencing or additional technical support).
Estimated Total for Contingencies: €500 - €1,000.

Similar genotypes .....................................................................................................

The domestic sheep (Ovis aries) has several well-characterized breeds, and the reference genome currently used for most genetic studies on sheep 
is based on the Texel sheep, a breed from the Netherlands. The Texel genome, first sequenced in 2014, is widely used in research and provides a 
high-quality reference for comparative genomics across sheep breeds.
However, in terms of genetic similarity, the Oveja Lacha, as a local Spanish breed, would likely share closer genotypes with other 
uropean or Mediterranean sheep breeds rather than with more distant breeds like Texel. Some genetically closer candidates include:

1. Churra Sheep (Spain)
Another Spanish breed, the Churra, shares a similar habitat and some genetic traits with the Oveja Lacha. 
Both are adapted to mountainous regions in Spain, making the Churra one of the closest relatives genetically and geographically.

2. Latxa Sheep (Basque Country and Navarre, Spain)
The Latxa is a local Basque sheep breed known for producing milk for Idiazabal cheese. 
This breed is closely related to the Oveja Lacha and would likely have similar genetic adaptations, 
as both are adapted to the Basque region’s terrain and climate.

3. Merino Sheep (Spain/Portugal)
The Merino breed is widely spread and genetically influential in sheep worldwide. 
While not as closely related to Oveja Lacha as the Churra or Latxa, it’s a Mediterranean breed and shares some genetic background.

4. Assaf Sheep (Spain/Israel)
Originally bred from Awassi and East Friesian sheep, Assaf is now common in Spain for dairy production. 
While not native, the Assaf shares some adaptive genetic traits with local breeds.

Recommendation for Genome Comparison
Using the Texel reference genome for initial assembly is common practice, as it is well-annotated and publicly accessible. 
However, for identifying breed-specific traits, comparing Oveja Lacha with Churra, Latxa, or Merino genomes 
would be ideal for insights into genetic adaptations specific to the Iberian Peninsula and mountainous environments.