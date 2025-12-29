Status: POLISH

## **Where the Money Goes**

> **Chapter Question:** How did the precision-medicine economy learn to monetize data long before it learned to represent the people who generate it?
> **Chapter Claim:** Every major discovery pipeline—from Penn to CHOP to Stanford to UCSF to UCF—was engineered to reward coded volume, not demographic accuracy, so the dividends naturally flowed upward to those already legible.
> **Exit Handoff:** Having followed the money through these systems, Chapter Three traces the deaths that accumulate wherever the data disappears.

I did not stumble into the mathematics of bias.

I was trained by the people who invented it.

Not the bias—the mathematics.

That distinction matters, because the villain of this chapter isn’t a person. It’s a design. It’s a set of incentives so old and so normalized that we stop seeing them as choices. We start seeing them as physics.

And physics, once you accept it, becomes destiny.

What I’m about to describe doesn’t require conspiracy. It doesn’t require a smoky room where executives plot exclusion. It doesn’t even require malice. The precision-medicine economy works the way it works for one simple reason:

once data can be turned into money, money will build a machine to collect it—once—and keep the dividends flowing—forever.

That is the logic of the digital age. Build once. Scale endlessly. Extract repeatedly. That’s why the great platforms—social networks, marketplaces, ad engines—are not “products.” They are pipes. You lay them down and the world’s value runs through them.

Marc Andreessen gave the culture its phrase for this: software is eating the world.

Healthcare is where that phrase stops being clever and starts being cruel, because healthcare is the one market where the buyer is desperate, the stakes are bodily, and the timeline is short. It is commerce under duress. And under duress, the moral theory we like to cite—free choice, informed consumers, market discipline—does not behave like morality. It behaves like appetite.

The patient does not enter the precision-medicine economy as a partner.

The patient enters as a substrate.

A source.

A sample.

A record.

A claim.

A coded event.

And then the machine goes to work.
 
## **Dividend One: Training the Eye to See Value**

By the time I entered the University of Pennsylvania’s MD/PhD program, biology had begun its irreversible transformation into an information science. Sequencing costs were falling. Computers were getting faster. The Human Genome Project was moving toward completion. A new kind of lab was emerging—one where the limiting reagent wasn’t a pipette tip, it was a programmer.

To a lay reader, “MD/PhD” can sound like a humble brag, so let me translate it plainly: it’s a dual-degree track where you begin medical school, then step out—sometimes for years—to do full-time research training, then step back into the hospital and finish the doctor part.

In my case, I started in medicine, then spent two years in systems engineering before returning—like a prodigal son with better self-knowledge—to a new discipline: Genomics and Computational Biology, one of the earliest formal homes for people who wanted to speak both languages—medicine and machine.

That detour mattered.

Because systems engineering taught me something the hospital rarely teaches explicitly: systems don’t reward effort; they reward alignment. If you speak the system’s language, you move. If you don’t, you stall.

Engineering at Penn was brilliant, intense, and—if I’m honest—humbling in a way I did not know I needed. The culture was math-fluent in a way that felt like a dialect spoken at speed. Many of the strongest students were Chinese. They weren’t “mean.” They weren’t exclusionary by intent. But the study groups moved like a current, and if you didn’t already swim that way, you spent your energy just trying not to drown.

I shared an office with the only other native English speaker in the cohort. He was Black. Brilliant. Eventually, like me, he left.

I used to joke that the main reason I wasn’t an engineer is I don’t speak Chinese.

It was a joke, yes—but it was also a coping mechanism. A way to smile at what felt like defeat. Because the truth was simpler and sharper:

they could speak math the way I could speak story.

And in engineering, math is the passport.

So I took the master’s degree and walked back across campus toward the other cathedral—Penn Medicine—just as the genome era opened its doors.

Back then, we didn’t have millions of human genomes the way we do now. The culture of genomics was still shaped by evolution—by cross-species comparison. The logic was elegant and brutally pragmatic: if a stretch of DNA stays the same across species, nature is protecting it. Conservation is signal.

It’s still true today, but the world has changed. Today we have oceans of within-human variation—population-scale sequencing—so the comparative lens is no longer the only telescope.

Back then? It was the telescope.

That was my world at Penn: half medicine, half machine, and a growing awareness that data was becoming the new substrate of biology—the soil from which careers, companies, and whole markets would grow.

And wherever a substrate becomes valuable, an economy forms around it.
 
## **Dividend Two: Volume**

My dissertation work lived at the intersection of neural genes and evolution—what stayed conserved, what changed, what mattered. My thesis committee was not a list of names to impress anyone; it was a structure of accountability. A thesis committee is the group of senior scientists responsible for ensuring you actually understand what you claim to understand. They question your assumptions. They poke at your methods. They insist you explain your results in human language when you try to hide behind technical phrasing.

It’s the closest thing academia has to a trial.

And in that room—week after week, season after season—I learned the first rule of modern discovery:

volume wins.

Not because volume is morally superior, but because volume produces statistical confidence, and confidence is currency in science.

This is where lay readers deserve a pause, because the word “genomics” gets thrown around like it’s magic. It isn’t.

Genomics is simply the study of the genome—the complete set of DNA instructions in a person’s cells. DNA is written in four chemical “letters.” A genotype is the particular pattern of those letters at specific points in the genome—like a fingerprint made of biology. A SNP (pronounced “snip”) is a single-letter variation—one tiny place where one person might have an A and another might have a G. It sounds small, but when you measure hundreds of thousands of SNPs across thousands of people, you can detect patterns that shape disease risk.

In the mid-2000s, that was big science.

And one of the great early resources for autism genetics was AGRE—the Autism Genetics Resource Exchange—families who volunteered their time, their blood, their stories, their grief. Parents desperate for answers. Families showing up, again and again, because when your child is struggling and you’re told “research is hope,” you show up.

The first time I analyzed one of those autism cohorts, I didn’t start with a sophisticated model.

I started with an Excel pivot table.

A pivot table is a blunt instrument: you take a spreadsheet and count categories. You ask the file a simple question:

Who is actually in here?

I pivoted the cohort by the ancestry labels recorded in the dataset. The output was not a poetry line. It was a number line:

European ancestry: ~99%
Everything else: the remainder—thin slices too small to carry statistical weight.

That’s what the table said.

And I remember the feeling that followed—not moral outrage yet, not ideology—just disbelief. I checked the table again. Same output.

This is the cold rule that governs discovery pipelines but rarely gets said plainly:

If you don’t have enough samples from a group, you cannot generate reliable conclusions about that group.

Small numbers don’t create clarity. They create noise.

Noise doesn’t publish well.
Noise doesn’t fund well.
Noise doesn’t become product.

So the machine does what machines do.

It narrows.

And we did what everyone did.

We dropped the outliers and carried on.

Not because anyone wanted to erase anyone. Because the system rewarded the path of least statistical resistance.

That is the second dividend:

a dataset that’s big enough—and clean enough—to produce effects.

And once you can produce effects, you can get grants, publish, build reputation, attract investors, file patents.

The families whose DNA created the dataset? They didn’t get a dividend.

They got a thank-you letter.

Maybe.
 
## **Dividend Three: The Basement Tree**

The pivot table bothered me because it felt too human. Labels are social. Labels are messy. If I was going to believe this, I wanted the biology itself to confirm it.

So I built an ancestry caller—an algorithm that infers ancestry from genetic markers. Not to reduce human beings to race, but to verify a dataset’s structure when self-report is incomplete, inconsistent, or absent.

The result was the same: the dataset was overwhelmingly European.

Then I went one step further and plotted a phylogenetic tree.

Here’s where I slow down, because “phylogenetic tree” is jargon that people nod at without seeing.

A phylogenetic tree is a map of relatedness. Think of it as a family tree, but for populations—or species—built from DNA rather than surnames. The underlying logic is simple:

DNA accumulates mutations over time at roughly measurable rates.
More time = more difference.
Less time = less difference.

So in a phylogenetic tree, “deep” versus “shallow” is about time—how long lineages have been diverging. “Broad” versus “narrow” is about frequency—how many samples you actually have.

And that’s what stunned me, sitting with Junhyong in the basement—dim light, quiet hum of machines, the campus above us living its life while we stared into genetic history on a screen:

The African clade was deep—because humans have lived there longest. That’s evolutionary time. The roots go down.

But it was also narrow in our dataset—because we had so few African-ancestry samples. That’s frequency. The branch was thin.

The European cluster, by contrast, was shallow—in evolutionary time, because that lineage is more recent—but broad in our dataset, because it dominated the file.

So the plot looked almost like a trident through fog: a long, deep, narrow African branch puncturing a wide, shallow European canopy.

It wasn’t ideology. It was history.

And it carried an economic implication that took me years to fully absorb:

When your dataset is dominated by a broad, shallow cluster, you get cleaner statistics. You get models that behave. You get associations that replicate. You get results that feel “precise.”

Precision is not just a scientific achievement.

It is a product feature.

And product features are how dividends begin.

At the time, we called this pragmatism.

We told ourselves we were just being rigorous.

And we were.

But we were also feeding an economy that would one day sell “precision” to the public without disclosing the boundary conditions of that precision.

I finished the PhD.

Life continued.

And the machine kept narrowing.
 
## **Dividend Four: The Cathedral at CHOP**

After Penn, I returned to clinical training and then into the part of the world where science stops being a paper and becomes a pipeline.

At CHOP—the Children’s Hospital of Philadelphia—there is a kind of reverence you feel the first time you walk through it. Not religious reverence. Institutional reverence. The sense that you are inside one of the great engines of pediatric medicine.

Across the street is West Philadelphia—predominantly Black, deeply rooted, deeply burdened by the same inequities every American city carries in its bones. CHOP sits against that reality like a fortress of excellence.

Inside CHOP, a new kind of center was coming into power: the Center for Applied Genomics (CAG)—an industrial machine for genotyping children at scale.

This is where I first met Hakon Hakonarson in that era: Icelandic by ancestry, big-science by temperament, running the center like a builder. If academia has poets, he wasn’t trying to be one. He was building an engine.

And engines produce outputs. Not just papers. Not just knowledge.

Value.

At NeuroFix—our precision-medicine venture in neuropsychiatry—I became lead bioinformatician on pediatric genotyping efforts at a scale that was breathtaking at the time: tens of thousands of children, hundreds of thousands of SNPs.

Put that in lay terms: we were taking a child’s biology and turning it into a dataset dense enough to compute on.

And then I asked the same question again:

Who is in the dataset?

The answer hit like a body blow:

over 99% White.

Not “mostly.” Not “skewed.” Not “needs improvement.”

A near-monoculture.

And here is where the book’s thesis begins to harden into something readers can feel in their teeth:

CHOP’s dataset—built beside a majority-Black community—barely represented that community.

The children across the street were absent from the genomic record defining the architecture of their diseases.

This isn’t symbolic exclusion.

This is economic exclusion.

Because those genotypes didn’t just generate knowledge.

They generated millions.

Let’s talk money without hype.

Genotyping at scale—especially at that time—was not a $10 blood test. Between lab processing, chips, quality control, informatics, storage, analysis, and the labor of the pipeline, a conservative all-in cost easily landed in the high hundreds to low thousands per sample depending on era and method.

So tens of thousands of children represent tens of millions of dollars of direct scientific capital.

Then comes the multiplier:
- Papers
- Grants
- Patents
- Pharma partnerships
- Licensing
- Startups
- Investment rounds
- Acquisitions

The first dataset is the seed.

The dividends are what keep paying long after the seed is planted.

And NeuroFix eventually sold for millions.

Here is the part that should make the reader physically uncomfortable:

none of those dividends went back to the families whose DNA made the value possible.

The patient—the literal source of the asset—does not get reimbursed.

The hospital bills.
The lab bills.
The insurer bills and denies and arbitrates.
The vendors bill.
The platforms monetize.
The investors exit.

The patient supplies the substrate and gets nothing but the bill.

If you want a single sentence that captures the moral inversion of the precision-medicine economy, it’s this:

everyone gets paid except the person who paid with their body.

Figure 2.1: From Data to Dividends

This is the moment you need the reader to see the machine in one glance.

Figure 2.1 (full-page): "From Data to Dividends: The Precision-Medicine Pipeline."
- Patients enter as bodies -> data.
- Small groups fall out as "insufficient N."
- What remains becomes code.
- Code routes upward into institutions, insurers, industry.
- Excluded patients remain below, carrying the risk of model failure.

(Insert Figure 2.1 here - "Figure_2_1_From_Data_to_Dividends.png")

The figure isn’t decoration.

It’s indictment.
 
## **Dividend Five: Stanford and the Rule That Governs Everything**

After CHOP, I went to Stanford for residency in Clinical Pathology and Laboratory Medicine—the specialty that lives behind the scenes, where medicine becomes measurable.

If you want to know how the healthcare economy truly works, go to pathology.

Pathology is where disease becomes a label. Where a diagnosis becomes something that can be recorded, transmitted, billed. Where biology becomes code.

At Stanford, I learned the simplest rule of American medicine:

If you can’t bill it, it won’t live.

This is where the vocabularies matter - not as acronyms, but as the alphabet of power:
- ICD: what you're diagnosed with
- CPT: what was done to you
- LOINC: what lab result you produced
- SNOMED: how concepts get normalized across systems

These aren’t “administrative.” They are the rails.

A new test can be brilliant.
It can save lives.
It can be scientifically correct.

But if it doesn’t fit into the coded pathways, it doesn’t become routine care.

And routine care is where scale happens.

At Stanford I also lived another truth: the training environment itself is a kind of machine. In my CP year there was essentially one other resident I truly ran alongside—an Israeli, Caltech-trained, the kind of mind that solves problems by seeing structure the way other people see color. We both left after the first year. Different exits, same conclusion:

some systems are not built to keep you; they are built to use you.

From Stanford, one of the most important projects I touched wasn’t a glamorous Silicon Valley use case.

It was dengue.

With Ben Pinsky, Stanford’s virology leadership, we worked on dengue prognostic validation in Trinidad—a place where the circulating serotype was available and the reality was immediate. Dengue is classified by the WHO among neglected tropical diseases.  The irony of “neglected” hits differently when you grew up in the tropics: you learn that the world’s attention isn’t allocated by suffering; it’s allocated by markets.

Prognostic testing in dengue is hard because severe cases are rare, and rarity is the enemy of statistical power. You need enough events to predict events. You need enough outcomes to model outcomes.

And again, I saw the same economic physics:

If a disease is concentrated in places without purchasing power, the pipeline moves slower.
If a disease is concentrated in places with insurers and reimbursement, the pipeline speeds up.

So when people tell you medicine is “about science,” they’re not lying.

They’re just incomplete.

American medicine is about codes.

Because codes are how money flows.
 
## **Dividend Six: UCSF and the Liquidity of Open Data**

At UCSF, I entered the era of open data at scale—repositories like GEO (the Gene Expression Omnibus), where tens of thousands of samples become downloadable files.

Open data is sold as democratization.

And in some ways, it is.

But open data has a shadow property that matters more in an economy:

open data is liquid.

It can move fast.
It can be reused endlessly.
It can be recombined into new claims.

And here’s the trap: when biased data becomes liquid, bias compounds.

A skewed dataset doesn’t just misrepresent once.

It misrepresents a thousand times.

Because every reuse inherits the shape of the original.

At UCSF, I watched this happen in real time. The same samples—drawn largely from the same populations—producing results that become “generalizable” through repetition, not through true representational breadth.

This is the network effect in scientific clothing:

Once a dataset becomes the standard reference, it attracts more users.
More users generate more papers.
More papers generate more citations.
More citations make it “canonical.”

And the canonical becomes the default.

You don’t even have to be malicious to participate.

You just have to be busy.

This is where “software is eating the world” becomes healthcare’s darker cousin:

data is eating medicine.

And the people who own the pipes get the dividends.
 
## **Dividend Seven: UCF, COVID, and the Price of Representation**

By the time I reached UCF, I had already lived inside the system long enough to recognize its reflexes.

Then COVID hit, and the system revealed itself in high contrast: the inequities that used to be buried in academic language became national headlines.

And when I launched decentralized trials—patients uploading imaging from home—the most sobering economic insight came not from a journal.

It came from advertising metrics.

Recruiting a White woman: under ~$200.
Recruiting a Black woman: over ~$9,000.

A 45-fold difference.

That isn’t bias as ideology.

That’s bias as price.

That’s the market charging interest on historical neglect.

The system doesn’t just exclude people.

It monetizes their exclusion—then bills you to correct it.
 
## **Dividend Eight: The Insurance Engine**

Now we have to name what most polite conversations avoid.

Why are there codes at all?

Because insurance needed a way to standardize reality so money could move at scale.

Insurance doesn’t run on empathy. It runs on categories.

And the more categories it has, the more precisely it can price you, deny you, and optimize profit around you.

That is why the codebook expanded.

That is why the “translation layer” of medicine became more valuable than the medicine itself.

This is not abstract. It is measurable.

U.S. healthcare spending is in the trillions—$4.9 trillion in 2023 per widely cited national estimates.  That money does not move as a single river. It moves through intermediaries: insurers, billing systems, risk scores, reimbursement policies. The code is the language of those flows.

And when the economy becomes code-driven, whoever controls coding controls outcomes.

This is where the dividends become grotesque.

A recent OIG-reported pattern (covered publicly) described billions in extra Medicare Advantage payments tied to diagnoses from insurer-initiated home visits, often without follow-up treatment—diagnosis as revenue event.

And then there’s the lawsuit story—the one that feels like the future arriving early.

A Reuters-reported case describes allegations around a company (owned by UnitedHealth) accused of using algorithmic risk scores that inflated risk and denied or delayed needed post-acute care for Medicare Advantage patients, with claims of rapid denials and pressure on clinicians.

Whether every allegation holds in court is for courts to decide.

But the architecture is already visible:
- diagnosis codes -> risk scores -> reimbursement -> denials
- data pipelines -> models -> policies
- policies -> money

And again, the patient is the only one not reimbursed.
 
## **The Dividend Summary: How the Trillions Assemble**

If you want readers to leave aghast, you don’t do it with outrage. You do it with arithmetic.

Here is the dividend logic, stacked:
1. Research volume dividend: tens of millions in cohort construction; billions in downstream grants, publications, and IP.
2. Reimbursement dividend: coded care becomes billable care; billable care becomes standard care.
3. Platform dividend: build the pipeline once; reuse endlessly (open data, EHR integration, AI models).
4. Network-effect dividend: the "standard dataset" becomes the default truth (citations, canon, inertia).
5. Insurance dividend: risk scoring turns diagnoses into revenue and denials into savings.
6. Equity surcharge: representation costs more - priced explicitly by the market.

Add it up and you don’t get “a big industry.”

You get an economy with gravity.

You get an economy that can plausibly sit under the umbrella of U.S. healthcare spending in the trillions.

And the central insult remains:

the patient generates the asset, but the patient doesn’t own the asset.
the patient funds the economy with their body, but the patient receives no dividend.

If this feels like theft, it’s because the word “theft” is what we call it in every other market.
 
Exit Handoff: Why Chapter Three Must Be Deaths

This chapter was the money.

Chapter Three is what the money leaves behind.

Because whenever a system optimizes for what is easiest to count, it will systematically neglect what is hardest to represent.

And neglected data becomes neglected people.

The dividends go up.

The deaths go down.

And that is why the next chapter exists.
