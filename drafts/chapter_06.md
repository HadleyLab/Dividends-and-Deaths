# CHAPTER SIX — THE UNDERREPRESENTED MAJORITY


The first time I understood what it meant to be unseen by the system I had devoted my life to did not come in a lecture hall or behind a glowing bioinformatics terminal. It happened during my residency at Stanford, inside a quiet exam room that smelled faintly of antiseptic and linoleum. I was reviewing the case of a woman in her early fifties, a home health aide who had discovered a breast lump months earlier but could not afford to miss a shift. When her record loaded on the screen, I stared at a void: no mammograms, no coded screenings, no prior biopsies, no receptor tests—nothing.

She lived twenty minutes from one of the most technologically advanced medical centers in the world. But in the genomic and clinical datasets that power modern precision medicine, she did not exist.

Years later, at UCSF, I would see that same pattern not in a single chart but across 80 million patient encounters spanning California. My NIH-funded work placed me at the center of statewide computational health research—EHR data, registries, claims, genomic repositories—a panoramic view of modern medicine’s digital nervous system. And again and again, the same ghostly absence appeared: patients whose lives were never captured in the structured codes that fuel precision medicine. Demographics missing. Diagnoses under-coded. Screenings unrecorded. Tumor subtypes absent. Genomic profiles nonexistent.

The population that suffered most was missing most.

But nothing cut deeper than the realization that this invisibility included me—and my three daughters.

We are Trinidadian, a blend of East Indian and African ancestries, descendants of a diaspora shaped by colonialism, indenture, and enslavement. Trinidadians are among the most genetically admixed populations on Earth. Yet we exist nowhere in the foundational datasets that define modern genomic science. Not in the Human Genome Project. Not in early GWAS. Not in large-scale sequencing panels. Not in the risk models used in oncology. Not in the imputation catalogs used by AI pipelines.

It struck me as I tucked my daughters into bed during those years at UCSF:
the very systems I was helping build had never been built for them.

⸻

The Fault Line at the Foundation

I started my PhD at Penn the same year the Human Genome Project (HGP) published its landmark results. In 2001, when the papers landed in Nature and Science, the scientific world celebrated as if we had discovered fire. Francis Collins and Eric Lander stood at the pinnacle of the genomic age. I was entering the field just as the ground beneath it seemed to glow with possibility. We believed we were laying the foundation of universal medicine.

But the foundation was not universal.

According to the National Human Genome Research Institute,
70% of the reference genome came from a single donor of blended ancestry,
and the remaining **30% from nineteen individuals—almost entirely of European descent.**¹

It was not a representative human genome.
It was a narrow sampling of a narrow corner of humanity.

The HGP was technically brilliant—astonishingly precise, reproducible, internally consistent. But precision is not the same as accuracy.

A perfectly precise model can be globally inaccurate if it is calibrated to the wrong reference frame.

And for reasons historical, logistical, and structural, the reference frame chosen for the human genome was fundamentally Eurocentric.

This was not just a scientific oversight. It was a biological miscalibration.

African populations contain the greatest genetic diversity of any humans on Earth—the deepest ancestral variation from which all non-African populations descend. Every European, Asian, Indigenous, and Pacific genome is simply a subset of that variation. Had the HGP sequenced an African individual, the result would have been broadly representative of all humanity.

Instead, we chose the opposite.
And for the next two decades, medicine built itself atop that choice.

Every alignment algorithm.
Every variant caller.
Every polygenic score.
Every GWAS.
Every imputation panel.
Every risk prediction tool.
Every “precision” model.

All of it grew from a reference sequence that left out most of the world.

⸻

The Consequences Become Visible

Nobody understood the stakes earlier or more forcefully than my UCSF colleague Esteban González Burchard, whose work remains some of the most damning evidence in modern medicine.

His findings read like indictments:
	•	**Puerto Rican children have the highest asthma prevalence in the world.**²
	•	**African American children are up to 10 times more likely to die of asthma.**²
	•	Yet asthma genomics was—and largely remains—built almost entirely on European cohorts.³

These were not small discrepancies.
These were signs of structural inaccuracy in the core of precision medicine.

The same pattern appeared in every disease I touched:

Kidney disease

APOL1 variants—common in African ancestry—raise CKD risk dramatically. They went undiscovered until 2010 because African genomes were largely absent from research data.⁴

Maternal mortality

Black women in the U.S. die during childbirth at three to four times the rate of White women—even when controlling for socioeconomic status.⁵ Precision models rarely address the structural determinants driving these disparities.

Breast cancer

Black women are 40% more likely to die from breast cancer, despite slightly lower incidence.⁶ Molecular subtyping, recurrence scores, and imaging AI all underperform for the very populations carrying the highest mortality.

Precision oncology trials

Across hundreds of studies, Black, Latino, and Indigenous patients remain underrepresented by as much as 60% relative to disease burden.⁷

Artificial intelligence

A Science analysis exposed an algorithm used in U.S. hospitals that systematically underestimated the health needs of Black patients because it used healthcare cost as a proxy for illness.⁸

The pattern was unmistakable:
People underrepresented in the data are overrepresented in the deaths.

The “precision” in precision medicine had become a form of systemic myopia.

⸻

A Personal Breaking Point

The deepest rupture came during the COVID-19 pandemic. I had just arrived at UCF, newly funded for breast cancer research, ready to crowdsource mammograms for algorithmic development when the world shut down. The pandemic exposed every inequity we had buried beneath decades of euphemisms.

Suddenly, everyone understood what social determinants of health really meant.
Suddenly, clinical trials—for the first time in modern memory—looked like America.
Suddenly, the populations long ignored became essential to the nation’s survival.

During that period, I launched a decentralized clinical study (NCT05384912) to collect COVID-19 imaging data. We used Facebook ads to recruit participants, believing technology could bypass the usual barriers.

Instead, technology revealed them.

It cost under $200 to recruit a White woman.
It cost over $9,000 to recruit a Black woman.

A forty-five-fold gap.
In a digital environment.
With no hospitals.
No waiting rooms.
No referrals.

A structural inequity so deep it could be measured in dollars per click.

It was the Human Genome Project rendered as an advertisement algorithm.

It was the same foundational miscalibration, replayed on a planetary scale.

⸻

The Underrepresented Majority

Standing in that rupture—between my Trinidadian daughters’ futures and the genomic world I helped build—I finally understood the central truth of this chapter:

The global majority was never included in the foundation of precision medicine.
And systems built on exclusion cannot produce equity, even when the science improves.

The “underrepresented minority” is not a minority.
It is the majority of humanity:
	•	most of Africa
	•	most of Asia
	•	most of the Caribbean
	•	most of Latin America
	•	most of Indigenous America
	•	most mixed-ancestry populations everywhere

People who represent the genetic breadth of humanity are barely represented in the systems meant to define human health.

And because they were not included at the foundation,
they do not receive the dividends of the precision-medicine economy today.

This is not a failure of sequencing technology.
This is not a failure of clinicians.
This is not a failure of patients.

This is a failure of calibration.

And the only way to correct it is to rewrite the architecture of precision medicine itself.

Part II ends here, because the next part begins the redesign.

⸻

## Selected References — Chapter Six

1. National Human Genome Research Institute (NHGRI). “Whose genome was sequenced by the Human Genome Project?” https://www.genome.gov/about-genomics/educational-resources/fact-sheets/human-genome-project
2. Nishimura KK, Galanter JM, Roth LA, et al. “Differential asthma risk among populations of varying genetic ancestry.” *PNAS.* 2015.
3. Burchard EG, et al. “The importance of race and ethnic background in biomedical research and clinical practice.” Summarized in *NEJM* and *PNAS* commentaries.
4. Genovese G., et al. “APOL1 genetic variants in African ancestry and kidney disease.” *NEJM.* 2010.
5. Petersen EE., et al. “Racial/Ethnic Differences in Pregnancy-Related Deaths.” *MMWR.* 2019.
6. Daly B., Olopade OI. “Disparities in Breast Cancer Mortality.” *NEJM.* 2022.
7. Loree JM., et al. “Racial and Ethnic Disparities in Precision Oncology Trials.” *JAMA Network Open.* 2021.
8. Obermeyer Z., et al. “Dissecting racial bias in an algorithm used to manage population health.” *Science.* 2019.
