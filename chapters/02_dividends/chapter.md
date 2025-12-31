Status: POLISH

## **Where the Money Goes**

> **Chapter Question:** How did the precision-medicine economy learn to monetize data long before it learned to represent the people who generate it?
> **Chapter Claim:** Every major discovery pipeline—from Penn to CHOP to Stanford to UCSF to the University of Central Florida (UCF)—was engineered to reward coded volume, not demographic accuracy, so the dividends naturally flowed upward to those already legible.
> **Exit Handoff:** Having followed the money through these systems, Chapter Three traces the deaths that accumulate wherever the data disappears.

I did not stumble into the mathematics of bias.

I was trained by the people who invented it.

Not the bias—the mathematics.

That distinction matters, because the villain of this chapter isn’t a person. It’s a design. It’s a set of incentives so old and so normalized that we stop seeing them as choices and start seeing them as physics.

And physics, once you accept it, becomes destiny.

What I’m about to describe doesn’t require conspiracy. It doesn’t require a smoky room where executives plot exclusion. It doesn’t even require malice. The precision-medicine economy works the way it works for one simple reason:

Once data can be turned into money, money will build a machine to collect it—once—and keep the dividends flowing—forever.

That is the logic of the digital age: build once, scale endlessly, extract repeatedly. That’s why the great platforms—social networks, marketplaces, ad engines—are not “products.” They are pipes. You lay them down and the world’s value runs through them.

Marc Andreessen gave the culture its phrase for this: software is eating the world.

Healthcare is where that phrase stops being clever and starts being cruel, because healthcare is the one market where the buyer is in crisis, the stakes are bodily, and the timeline is short. It is commerce under duress. Under duress, the moral theory we like to cite—free choice, informed consumers, market discipline—does not behave like morality. It behaves like appetite.

The patient does not enter the precision-medicine economy as a partner.

The patient enters as a substrate.

A source.

A sample.

A record.

A claim.

A coded event.

And then the machine goes to work.

This chapter is the story of that machine—told through the places that trained me, the mentors who sharpened me, the datasets that seduced me, and the arithmetic that made the whole thing impossible to unsee.

Not outrage.

Arithmetic.

The most haunting thing about this economy is not that it’s evil.

It’s that it’s efficient.

## **Dividend One: Training the Eye to See Value**

By the time I entered the University of Pennsylvania’s MD/PhD program, biology was already becoming an information science. Sequencing costs were falling. Computers were getting faster. The Human Genome Project was moving toward completion. A new kind of lab was emerging—one where the limiting reagent wasn’t a pipette tip, it was a programmer.

Penn was the right place to feel that shift in your bones.

This wasn’t just another campus with ivy on the walls. Penn carries a specific kind of American gravity. It doesn’t just teach medicine—it helped invent American medical education. The Perelman School of Medicine traces back to 1765 and is widely recognized as the first medical school in the United States.  ￼

And Penn also sits near another origin story—one that feels like a prophecy when you’re living a double life between biology and computation. Across the same city, within the same institutional ecosystem, the early architecture of modern computing was being forged—machines that turned human thought into symbols a device could process. You can feel it in Philadelphia if you know what you’re listening for: the hum of old ideas still powering new ones.

To a lay reader, “MD/PhD” can sound like a humble brag. Here is the plain translation: it’s a dual-degree track where you begin medical school, step out—sometimes for years—for full-time research training, then step back into the hospital to finish the doctor part. You learn two languages: the language of bodies and the language of evidence. You learn to move between bedside and bench without pretending they are the same world.

In my case, I started in medicine, then spent two years in systems engineering before returning—like a prodigal son with better self-knowledge—to a new discipline: Genomics and Computational Biology, one of the earliest formal homes for people who wanted to speak both languages—medicine and machine.

That detour mattered. Systems engineering taught me something the hospital rarely teaches explicitly: systems don’t reward effort; they reward alignment. If you speak the system’s language, you move. If you don’t, you stall.

Engineering at Penn was brilliant, intense, and—if I’m honest—humbling in a way I did not know I needed. The culture was math-fluent in a way that felt like a dialect spoken at speed. Many of the strongest students were Chinese. The study groups moved like a current; if you didn’t already swim that way, you spent your energy just trying not to drown.

I shared an office with the only other native English speaker in the cohort. He was Black. Brilliant. Eventually, like me, he left.

I used to joke that the main reason I wasn’t an engineer is I don’t speak Chinese.

It was a joke, yes—and a coping mechanism. A way to smile at what felt like defeat. The truth underneath was simpler and sharper:

They could speak math the way I could speak story.

And in engineering, math is the passport.

So I took the master’s degree and walked back across campus toward the other cathedral—Penn Medicine—just as the genome era opened its doors.

Back then, we didn’t have millions of human genomes the way we do now. The culture of genomics was still shaped by evolution—by cross-species comparison. The logic was elegant and brutally pragmatic: if a stretch of DNA stays the same across species, nature is protecting it. Conservation is signal.

It’s still true today, but the world has changed. Today we have oceans of within-human variation—population-scale sequencing—so the comparative lens is no longer the only telescope.

Back then? It was the telescope.

That was my world at Penn: half medicine, half machine, and a growing awareness that data was becoming the new substrate of biology—the soil from which careers, companies, and whole markets would grow.

And wherever a substrate becomes valuable, an economy forms around it.

## **A Quick Inventory of the Jargon You’re About to See**

Before we go further, I owe the lay reader an honest map.

- **Genome:** the complete set of DNA instructions in your cells.
- **Genomics:** studying the whole genome at scale, usually by measuring many parts of DNA at once and looking for patterns.
- **Genotype:** your specific DNA “letters” at particular positions—like a biological spelling pattern.
- **Variant:** a place where one person’s DNA differs from another’s.
- **SNP (pronounced “snip”):** a single DNA-letter change at a single position. It sounds tiny. But measured across thousands of people and hundreds of thousands of positions, it becomes a statistical instrument.
- **Cohort:** a group of people gathered for study—often families, patients, volunteers.
- **Statistical power:** the ability to detect a real signal rather than mistake noise for truth. Power grows with sample size.
- **Bias (as we’ll use it here):** not moral failure; a systematic skew introduced by what gets collected, who gets collected, and what the pipeline rewards.

Keep that list in your back pocket. I’ll reintroduce terms when they return, like characters.

Because in a book like this, jargon isn’t just vocabulary. It’s the invisible scaffolding holding up an entire economy.

## **Dividend Two: Volume**

My dissertation work lived at the intersection of neural genes and evolution—what stayed conserved, what changed, what mattered. My thesis committee was not a list of names to impress anyone; it was a structure of accountability. A thesis committee is the group of senior scientists responsible for ensuring you actually understand what you claim to understand. They question your assumptions. They poke at your methods. They insist you explain your results in human language when you try to hide behind technical phrasing.

It’s the closest thing academia has to a trial.

And in that room—week after week, season after season—I learned the first rule of modern discovery:

Volume wins.

Not because volume is morally superior, but because volume produces statistical confidence, and confidence is currency in science.

In the basement—because the best kind of thinking in academia often happens below ground, away from windows, away from the campus theater—we read Motoo Kimura. Junhyong Kim, Korean, trained me to think in population genetics the way an engineer thinks in constraints: not as romance, not as vibes, but as structure.

Here’s the gentle translation for the reader: Kimura’s neutral theory is the idea that much of genetic change is driven not by dramatic survival battles, but by randomness—drift—quiet fluctuations accumulating over time.

To most people, evolution is Darwin in popular form: struggle, selection, winners and losers.

Kimura is the uncomfortable counterweight: the universe doesn’t always care; sometimes patterns emerge because probability did what probability does.

And here’s why this matters for this book:

When you build discovery pipelines on “what replicates,” you build pipelines that love the clean, the abundant, the statistically powerful. You build pipelines that punish the rare, the messy, the underrepresented.

That’s not ideology. It’s the math.

Junhyong could speak that math with a fluency that reminded me—painfully, productively—of the systems engineering rooms I’d just left. That same sensation: the system has a language; you either learn it or you watch the current take you.

And then there was Maja Bucan, Croatian, who grounded all that abstraction in wet lab reality. If Junhyong taught the grammar of populations, Maja taught the grammar of molecules—the literal feel of early training: gels, bands, ladders, the smell of buffers, the quiet discipline of doing the same thing again because biology doesn’t care that you’re tired.

A gel—for the lay reader—is a slab you run DNA through using electricity. DNA moves through it like people moving through a crowded city: some pieces travel faster, some slower. The result is visible bands—evidence you can point to. In a world of theory, the gel is your receipt.

And then there was Warren Ewens, Australian, on my thesis committee. He was the only one from the British Commonwealth. He and I would drift into Australia versus West Indies Test cricket, and for me Brian Lara was still the greatest batsman of his era, from Trinidad and Tobago.

Warren carried the kind of quiet authority that doesn’t need to announce itself. His presence in that room wasn’t about flash. It was about standards. The kind of standards that make you realize you’re not just learning facts—you’re being shaped by a lineage.

The jargon map above is the shorthand; in the mid-2000s, it was big science.

And one of the great early resources for autism genetics was AGRE—the Autism Genetics Resource Exchange—families who volunteered their time, their blood, their stories, their patience. Parents showed up again and again. The recruitment letters said “research is hope,” and the families kept coming.

The first time I analyzed one of those autism cohorts, I didn’t start with a sophisticated model.

I started with an Excel pivot table.

A pivot table is a blunt instrument: you take a spreadsheet and count categories. You ask the file a simple question:

Who is actually in here?

I pivoted the cohort by the ancestry labels recorded in the dataset. The output was not poetry. It was a number line:

European ancestry: ~99%
Everything else: the remainder—thin slices too small to carry statistical weight.

That’s what the table said.

And I remember the feeling that followed—not moral outrage yet, not ideology—just disbelief. I checked the table again. Same output.

This is the cold rule that governs discovery pipelines but rarely gets said plainly:

If you don’t have enough samples from a group, you cannot generate reliable conclusions about that group.

Small numbers don’t create clarity. They create noise.

Noise doesn’t publish, doesn’t fund, doesn’t become product.

So the machine narrows. We did what everyone did: dropped the outliers and carried on.

Not because anyone wanted to erase anyone. Because the system rewarded the path of least statistical resistance.

That was the dividend: coded volume that could produce effects. (See Figure 2.1.)

Figure 2.1 — The Precision-Medicine Dividend Stack

Figure 2.1 | The Precision-Medicine Dividend Stack. Patient data enters the medical system through biospecimens, imaging, and genotyping. Once translated into standardized codes, it becomes legible to reimbursement systems, research consortia, and AI pipelines. Economic value flows upward through grants, publications, and commercialization, while demographic distortion compounds wherever representation is sparse or dropped for statistical power.

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

CHOP’s origin story carries weight for a reason: it was founded in the mid‑19th century and is widely recognized as the first hospital in the United States devoted exclusively to children.

Across the street is West Philadelphia—predominantly Black, deeply rooted, deeply burdened by the same inequities every American city carries in its bones. CHOP sits against that reality like a fortress of excellence.

Inside CHOP, a new kind of center was coming into power: the Center for Applied Genomics (CAG)—an industrial machine for genotyping children at scale.

This is where I first met Hakon Hakonarson in that era: Icelandic by ancestry, big-science by temperament, running the center like a builder. If academia has poets, he read as an engineer of scale.

Engines produce outputs. Not just papers or knowledge.

Value.

At NeuroFix—our precision-medicine venture in neuropsychiatry—I became lead bioinformatician on pediatric genotyping efforts at a scale that was breathtaking at the time: tens of thousands of children, hundreds of thousands of SNPs.

Plainly: we were taking a child’s biology and turning it into a dataset dense enough to compute on.

I asked the same question again:

Who is in the dataset?

The answer hit like a body blow:

Overwhelmingly White.

Not “mostly.” Not “skewed.” Not “needs improvement.”

A near-monoculture.

Here the book’s thesis begins to harden into something readers can feel in their teeth:

CHOP’s dataset—built beside a majority-Black community—barely represented that community.

The children across the street were absent from the genomic record defining the architecture of their diseases.

This isn’t symbolic exclusion.

It is economic exclusion.

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

Here is the part meant to land physically:

None of those dividends went back to the families whose DNA made the value possible.

The patient—the literal source of the asset—does not get reimbursed.

The hospital bills. The lab bills. The insurer bills, denies, arbitrates. Vendors bill. Platforms monetize. Investors exit.

The patient supplies the substrate and gets nothing but the bill.

If you want a single sentence that captures the moral inversion of the precision-medicine economy, it’s this:

Everyone gets paid except the person who paid with their body.

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

If you want to know how the healthcare economy really works, go to pathology.

Pathology is where disease becomes a label, where a diagnosis can be recorded, transmitted, billed, where biology becomes code.

At Stanford, I learned the simplest rule of American medicine:

If you can’t bill it, it won’t live.

Here the vocabularies matter—not as acronyms, but as the alphabet of power:
- ICD: what you're diagnosed with
- CPT: what was done to you
- LOINC: what lab result you produced
- SNOMED: how concepts get normalized across systems

These aren’t “administrative.” They are the rails.

Codes are not neutral.

A new test can be brilliant, lifesaving, and scientifically correct.

But if it doesn’t fit into the coded pathways, it doesn’t become routine care.

And routine care is where scale happens.

Stanford taught me another truth: the training environment itself is a kind of machine. In my clinical pathology (CP) year there was essentially one other resident I truly ran alongside—an Israeli, Caltech-trained, the kind of colleague who solved problems in the room faster than anyone else. We both left after the first year. Different exits, same conclusion:

Some systems are not built to keep you; they are built to use you.

From Stanford, one of the most important projects I touched wasn’t a glamorous Silicon Valley use case.

It was dengue.

With Ben Pinsky, Stanford’s virology leadership, we worked on dengue prognostic validation in Trinidad—a place where the circulating serotype was available and the reality was immediate. Dengue is classified by the World Health Organization (WHO) among neglected tropical diseases. The irony of “neglected” hits differently when you grew up in the tropics: you learn that the world’s attention isn’t allocated by suffering; it’s allocated by markets.

Prognostic testing in dengue is hard because severe cases are rare, and rarity is the enemy of statistical power. You need enough events to predict events. You need enough outcomes to model outcomes.

I saw the same economic physics again:

If a disease is concentrated in places without purchasing power, the pipeline moves slower.
If a disease is concentrated in places with insurers and reimbursement, the pipeline speeds up.

So when people tell you medicine is “about science,” they’re not lying.

They’re just incomplete.

American medicine is about codes.

That’s how money flows.

Around that same era, the wider tech world was shifting in ways that made the convergence feel inevitable: Bitcoin moving from obscure to discussable; deep learning’s modern arc accelerating; GPUs—graphics processing units—becoming the new industrial engine. The air was changing. The pipes were being laid.

So I turned toward systems medicine—not as branding, but as the only way I knew how to stay honest.

That’s where Atul Butte enters my story: not as an icon, not as mythology—simply as the person whose lab was building the kind of bridge I’d been trying to build since I was a kid staring at a blinking cursor.

He looked at my trajectory—Penn, genomics, CHOP, pipelines—and he said, in effect: come do this work for real.

I quit residency after the first year.

I wasn’t walking away from medicine.

I was walking toward a different way of practicing it.

## **Dividend Six: UCSF and the Liquidity of Open Data**

At UCSF, I entered the era of open data at scale—repositories like GEO (the Gene Expression Omnibus), where tens of thousands of samples become downloadable files.

Open data is sold as democratization.

In some ways, it is.

But open data has a shadow property that matters more in an economy:

Open data is liquid—it moves fast, reuses endlessly, and recombines into new claims.

And here’s the trap: when biased data becomes liquid, bias compounds.

A skewed dataset doesn’t just misrepresent once.

It misrepresents a thousand times.

Because every reuse inherits the shape of the original.

At UCSF, I watched this happen in real time. The same samples—drawn largely from the same populations—producing results that became “generalizable” through repetition, not through true representational breadth.

That is the network effect in scientific clothing:

Once a dataset becomes the standard reference, it attracts more users.
More users generate more papers.
More papers generate more citations.
More citations make it “canonical.”

And the canonical becomes the default.

You don’t even have to be malicious to participate.

You just have to be busy.

This is where “software is eating the world” becomes healthcare’s darker cousin: data is eating medicine.

And the people who own the pipes get the dividends.

## **Dividend Seven: UCF, COVID, and the Price of Representation**

By the time I reached the University of Central Florida (UCF), I had already lived inside the system long enough to recognize its reflexes.

Then COVID hit, and the system revealed itself in high contrast: the inequities that used to be buried in academic language became national headlines.

And when I launched decentralized trials—patients uploading imaging from home—the most sobering economic insight came not from a journal.

It came from advertising metrics.

Recruiting a White woman: hundreds of dollars.
Recruiting a Black woman: thousands of dollars.

An order‑of‑magnitude difference.

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

And the more categories it has, the more precisely it can price you, deny you, and optimize profit around you. That is why the codebook expanded. That is why the “translation layer” of medicine became more valuable than the medicine itself.

This is not abstract. It is measurable.

U.S. healthcare spending is in the trillions. That money does not move as a single river. It moves through intermediaries: insurers, billing systems, risk scores, reimbursement policies. The code is the language of those flows.

And when the economy becomes code-driven, whoever controls coding controls outcomes.

By then I already knew the first rule from Chapter One: The billable code is the fundamental economic unit of American healthcare.

This is where the dividends become grotesque.

A recent Office of Inspector General (OIG)‑reported pattern (covered publicly) described billions in extra Medicare Advantage payments tied to diagnoses from insurer‑initiated home visits, often without follow‑up treatment—diagnosis as revenue event.

There is also the lawsuit story—the one that feels like the future arriving early.

A Reuters‑reported case describes allegations around a company (owned by UnitedHealth) accused of using algorithmic risk scores that inflated risk and denied or delayed needed post‑acute care for Medicare Advantage patients, with claims of rapid denials and pressure on clinicians.

Whether every allegation holds in court is for courts to decide.

But the architecture is already visible:
- diagnosis codes -> risk scores -> reimbursement -> denials
- data pipelines -> models -> policies
- policies -> money

And again, the patient is the only one not reimbursed.

Interlude: What we know so far

Codes make care legible. Legibility creates volume. Volume creates credibility. Credibility attracts money. Money builds more pipes. The pipes reward what they can read and discard what they cannot. That is not a conspiracy; it is a design pattern. The dividends rise to those who are already legible. The costs fall to those who are not.

## **The Dividend Summary: How the Trillions Assemble**

If you want readers to leave aghast, you don’t do it with outrage. You do it with arithmetic.

Here is the dividend logic, stacked:
1. Research volume dividend: tens of millions in cohort construction; billions in downstream grants, publications, and IP.
2. Reimbursement dividend: coded care becomes billable care; billable care becomes standard care.
3. Platform dividend: build the pipeline once; reuse endlessly (open data, EHR integration, AI models).
4. Network-effect dividend: the "standard dataset" becomes the default truth (citations, canon, inertia).
5. Insurance dividend: risk scoring turns diagnoses into revenue and denials into savings.
6. Equity surcharge: representation costs more - priced explicitly by the market.

Add it up and you don’t get “a big industry.” You get an economy with gravity, one that can plausibly sit under the umbrella of U.S. healthcare spending in the trillions.

And the central insult remains:

The patient generates the asset, but the patient doesn’t own the asset.

The patient funds the economy with their body, but the patient receives no dividend.

Dividends rise. Deaths fall.

If this feels like theft, it’s because the word “theft” is what we call it in every other market.

## **Exit Handoff: Why Chapter Three Must Be Deaths**

This chapter followed the money. The system is functioning exactly as designed. Dividends flow upward. Omissions flow downward.

Chapter Three follows what the money leaves behind.

Dependencies: Figure 2.1 — figure_02_01_dividend_stack.png
