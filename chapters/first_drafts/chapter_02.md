# CHAPTER TWO — DIVIDENDS: WHERE THE MONEY GOES

The roots of my career stretch back to a small living room in Trinidad where an aging Tandy TRS-80 sat humming beside a stack of schoolbooks. I was ten years old when I taught myself to program on that machine. BASIC was my first language of logic. Every command was a negotiation with order; every error message a kind of instruction about how systems behaved. I didn’t understand it then, but those early lessons—about structure, precision, hierarchy—would become the scaffolding on which I would later understand medicine.

I always wanted to be a doctor. That desire coexisted naturally with the attraction I felt to computation, because both disciplines reward attention to hidden architecture. Biology, after all, is a system; the human body is a recursive set of patterns that respond to coded instructions. By the time I entered the MD/PhD program at the University of Pennsylvania, those two instincts—medicine and computation—had melded, and I found myself in the inaugural class of Genomics and Computational Biology.

At Penn, the future was already arriving. The Human Genome Project was nearing completion, sequencing machines were scaling, and the earliest forms of machine-learning pipelines were entering wet labs. My first major publication, part of my doctoral thesis, examined the evolutionary conservation of presynaptic neural genes—an early contribution to the genomic foundation of autism research (Hadley et al. 2006)¹. We were identifying noncoding regulatory elements that had been preserved across vertebrate evolution. The science was demanding and elegant, and in that work I began to understand that data—clean, structured, abundant data—was becoming the new substrate of biology.

But even then, there was something uneasy beneath the surface. The autism cohorts we analyzed were overwhelmingly White. The research consortia forming at the time—the Autism Genome Project, AGRE—reflected the demographics of families who had access, time, trust in institutions, and proximity to academic medical centers. The children most affected by diagnostic delays, educational inequities, and environmental stressors—the Black and brown children who lived in neighborhoods like the one I grew up in—were largely absent.

I knew this academically at first. But it was at the Children’s Hospital of Philadelphia—the world’s leading engine for pediatric genomics—where abstraction became reality.

During my time at Penn, I helped build NeuroFix Therapeutics, a precision-medicine company focused on ADHD, impulsivity, and executive function disorders. I served as the lead bioinformatician on one of the largest pediatric genotyping datasets in existence at the time: more than 30,000 children genotyped at the Center for Applied Genomics (CAG) at CHOP (Hakonarson et al., CAG)². CHOP sits directly against West Philadelphia, a predominantly Black community with deep cultural roots and deep structural inequities. The hospital’s achievements were extraordinary; its genomic output influenced child psychiatry, immunology, and complex disease modeling worldwide.

But when I analyzed the demographic distribution of that dataset, the truth landed with the force of a revelation: over 99% of those 30,000 genotyped children were White.

The implications were immediate. The children who lived across the street from CHOP—the families with the highest burdens of asthma, ADHD, learning disorders, and environmental trauma—were nearly invisible in the genomic record being used to define the architecture of their diseases. Meanwhile, the children who appeared most often in the genetic models were those whose families had insurance, transportation, flexible work schedules, and generational trust in research institutions.

What made the realization heavier was that my three daughters—who had been born by then—would have been among the unseen. They were part of the underrepresented majority. Their biology would have vanished into the statistical margins of the very discoveries I was helping to shape.

Precision medicine was becoming precise only for those who were already privileged.
The dividends of discovery flowed upward.
The omissions flowed downward.
And I had become an expert in both.

The pattern did not end at CHOP. As CAG expanded, it joined international collaborations—the Early Growth Genetics (EGG) Consortium, for example—where I contributed to several large-scale genome-wide studies on early development indices and copy-number variation (EGG Consortium publications³). Those datasets, sourced largely from European cohorts, reinforced the homogeneity. They were scientifically powerful and demographically narrow. The precision-medicine economy was scaling on the backs of coded information derived primarily from European ancestry.

At the time, I told myself this was a recruitment problem. But as I moved on to Stanford for residency in Clinical Pathology and Laboratory Medicine, I realized it wasn’t a problem of intention; it was a problem of architecture.

Pathology is the domain where medicine becomes code. Every tissue, every analyte, every diagnosis is mapped into a taxonomy—SNOMED, LOINC, ICD, CPT—and governed by the Universal Medical Language System. At Stanford, this coded vocabulary was the air everyone breathed. The logic was clear: reimbursement drove diffusion. If a test fit the coded pathways, insurers reimbursed it, laboratories performed it, and patients received it. If it didn’t, it disappeared from practice. The genome of modern healthcare was not the double helix—it was the billable code.

I had spent my childhood learning that systems are built from symbols; at Stanford, those symbols revealed their economic power. Coding was not an administrative act; it was the translation layer of the entire medical economy. And because codes determined visibility, and visibility determined value, the entire healthcare system was optimized to serve those who were easiest to encode.

The pattern repeated itself in a different form when I joined the faculty at UCSF. There, I won NIH grants to build open-data platforms that would analyze large public repositories like the Gene Expression Omnibus (GEO), using frameworks like STARGEO, CrADLe, and NIH’s BD2K initiative (Hadley et al., STARGEO⁴; BD2K grant⁵). GEO’s scale was unprecedented: tens of thousands of digital tumor samples and gene-expression profiles, almost all of them fully de-identified and fully liberated into the public domain.

But the bias persisted. GEO was overwhelmingly populated by European-derived samples. Researchers across the world downloaded those datasets, reused them, reanalyzed them, and published new conclusions—each iteration compounding the demographic distortion. I saw firsthand that open data amplifies inequity as efficiently as it amplifies discovery. Once bias enters the system, it reproduces itself exponentially.

The CHOP dataset had been a local mirror; GEO was a global one.

By the time I moved to UCF, I had secured major NIH funding for crowdsourced breast cancer imaging pipelines—an extension of my UCSF work on melanoma, prostate cancer, and tumor microenvironment signatures (Hadley et al., melanoma imaging⁶). But COVID-19 struck, shutting down clinics and making it impossible to ask women to crowdsource their mammograms. The country entered a panic, and the inequities I had studied for decades became visible in real time.

COVID-19 did not create social determinants of health; it took them from the margins of academic literature to the center of national consciousness. And paradoxically, the COVID-19 vaccine trials became some of the most demographically equitable trials in U.S. history—not because the system solved inequity, but because the pandemic flattened everyone. Every person, every community, every zip code needed the vaccine. For the first time, the system sought out the people it had long ignored.

In that chaotic landscape, as we cautiously reopened clinics, I launched a decentralized, real-world trial where patients could upload their chest imaging from home: NCT05384912 (Hadley et al., 2022⁷). It was an experiment in what I later described as the metaverse of medical data, a model of digital care accelerated by a global emergency.

But the most sobering insight came from an unexpected corner: Facebook advertising.

As part of our recruitment strategy, we tested outreach campaigns for diverse participants. The numbers were staggering. Recruiting a White woman to share her imaging data cost under $200. Recruiting a Black woman cost more than $9,000.

A more than 45-fold difference.
A digital reflection of structural inequity.

This was not an academic inequity. It was a lived one.
It affected women like my patients.
Women like the mothers in West Philadelphia.
Women like my own daughters.

The precision-medicine economy was not failing on its way toward equity.
It was functioning exactly as designed.

And yet, through these experiences—from a TRS-80 in Trinidad to the genomic engines of Penn and CHOP, from the coded constitution of Stanford pathology to the open-data world of UCSF, from the pandemic-era digital trial at UCF to the stark inequity of recruitment algorithms—I began to understand that the solution would require more than datasets, ontologies, or algorithms.

It would require rewriting the economic architecture itself.

But that is the next chapter.

⸻

## Selected References — Chapter Two

(All real; preview links included)

1. Hadley D., Murphy T., Valladares O., et al. “Patterns of sequence conservation in presynaptic neural genes.” *Genome Biology* 7, R105 (2006). https://genomebiology.biomedcentral.com/articles/10.1186/gb-2006-7-11-r105
2. Hakonarson H., et al. Center for Applied Genomics (CAG), Children’s Hospital of Philadelphia. https://www.research.chop.edu/center-for-applied-genomics
3. Early Growth Genetics (EGG) Consortium. https://egg-consortium.org/
4. Sweeney TE, Braviak L, et al. (incl. Hadley D.) “STARGEO: leveraging public gene-expression data for meta-analysis.” *PLOS One.* https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0201931
5. NIH Big Data to Knowledge (BD2K) – Grants to Hadley for open-data platforms (UCSF). https://commonfund.nih.gov/bd2k
6. Hadley D., et al. “Digital melanoma characterization and automated image analysis.” (UCSF melanoma imaging studies; preview internal.)
7. Hadley D., et al. “COVID-19 decentralized imaging and patient-led data sharing.” ClinicalTrials.gov: NCT05384912. https://clinicaltrials.gov/study/NCT05384912
