## Materials and Methods:

### Generation of miRNA library:
We obtained 40 UAS-DsRed-pre-miRNA constructs from the *Drosophila* RNAi Screening Center (http://www.flyrnai.org) that were originally published by Silver et al{Silver:2007hz}. Using overlapping oligos (5'-CGCGTTTAGAGTGGAGTACGCGCCCGGGGAGCCCAAGGGCACGCCCTGGCACCCGCACCGCGGTATACAATTCA-3' and 5'-CGCGTGAATTGTATACCGCGGTGCGGGTGCCAGGGCGTGCCCTTGGGCTCCCCGGGCGCGTACTCCACTCTAAA-3'), we modified these vectors by adding minimal attB sites into the MluI site to make them suitable for site-specific insertion into the fly genome. To produce the rest of the stocks, we modified the pKC27-derived attB-containing SST13 UAS vector, which makes use of the split-white system to reduce the time spent on off-target insertions{Bischof:2007cb}. We inserted additional restriction sites between the KpnI and XbaI sites of the SST13 polylinker using overlapping oligos (5’-CTAGAGCGAGCTCAAGGCCACTAGGGCCGGGATCGATATGGTAC-3’and 5’ CATATCGATCCCGGCCCTAGTGGCCTTGAGCTCGCT-3’). Inspired by the design of the Silver et al. UAS-miRNA vectors{Silver:2007hz}, we also inserted the DsRed coding sequence downstream of a 5X UAS sequence and renamed this vector pSS-DsRed. Next, we amplified putative pri-miRNA sequences consisting of roughly 400-500 bp surrounding each mature miRNA sequence from Canton S or w1118 genomic DNA and inserted them into pSS-DsRed. In the cases of the cluster miRNA, similar amount of the pri- miRNA region was added. Most miRNAs were cloned using TA cloning vector, pGEMT Easy and subcloned into attB containing vector pSS-Dsred/mCherry, while others were cloned directly. We validated all the UAS-miRNA vectors with restriction digests and sequencing. See supplemental table 1 for a summary of these UAS-miRNA constructs and the primers used to make them. After completing the UAS-miRNA constructs, we prepared and injected them into embryos of the attP 72A landing site strain using standard transgenesis techniques.

## Confirming tissue-specific miRNA-overexpression:
We confirmed the expression of our UAS-miRNA fly lines by crossing them to the wing driver nubbin-Gal4 and the eye driver GMR-Gal4. We were able to observe DsRed fluorescence in these lines a proxy of miRNA expressioN. We also observed developmental defects in both the eyes for GMR-Gal4 and the wing for nubbin-Gal4 (Fig. S1B and S1C). Several of the wing phenotypes are very similar to the wing defects previously published for overexpression of various miRNAs using other wing driver lines{Bejarano:2012gi, Schertel:2012eg}. We also directly verified the overexpression of the mature miRNA in a few select lines using qPCR with commercial TaqMan probes (data not shown).


### MicroRNA over-expression screen:
When we started this project, there were no UAS-miRNA stocks available; only a group of plasmids capable of driving miRNA expression when used to transform fly embryos had been made available\cite{Silver:2007hz}. 
Virgin flies containing Pebbled-GAL4, UAS-Dicer2, and the OR promoter fusions of OR47b and Or92a were mated with the males obtained from the UAS-miRNA library. The crosses were step up at 25^0, and at the pre-pupal stage vials were shifted to 27^0 until eclosion. 3d-4d post eclosion, brain immunostaining were performed as a score for loss of GFP expression. UAS-miR lines showing loss of GFP in either of ORs were re-tested for the reproducibility.

### MicroRNA target prediction:
miRNAs that gave rise to loss of OR expression phenotype were analysed by bioinformatic programs like TargetScan, PITA and miRanda.
For a given miRNA.  Targets were predicted first by making a list of predicted targets that comes out by TargetScan UTR and ORF, and list that predicts overlapping targets between ORF and UTR was made.
A  list of predicted targets for given miRNA was  also drawn from PITA and miRanda bioinformatics tools and common targets predicted amongst all 3 bioinformatic tools (PITA, miRanda and TargetScan) was then pooled to make a list.
The list of predicted targets were then run through the TargetScan, (UTR and ORF) to see if those targets bring out the same miRNA with better seed pairing.
A list of the targets with better seed pairing was made also made.
If two bioinformatics program predicted a common target, it was also retained for further validation.
When two miRNAs that gave same phenotype, overlapping target amongst it was given preference, followed by if the same target was predicted by two or more bioinformatic tool.
Finally predicted targets were then run through the microcosm, just to check, if it gives a better free energy change before ordering RNAi.

### Secondary RNAi screen: 
Virgin flies from Pebbled-GAL4,UAS-Dicer2 and the OR promoter fusions were crossed to male RNAi flies obtained from VRDC library. The crosses were carried out at 25^0 and the vials were moved to 28^0 at white pupal stage until the eclosure. The flies were incubated at 2-3 days post elcosure at 28^0 and  brains were immunostained for loss of GFP expression. The RNAi lines that gave loss were validated for reproducibility. To further validate the established phenotype, RNAi lines from DGRC were used and only the lines that gave same phenotype were considered positive hit and retained for further analysis.

###  Immunostaining and *in situ* Hybridization:
Immunostaining and in situ hybridization were performed as previously described. (refer Vosshall et al.).  The OR probes used for the in situ hybridization were cloned into pGEM-T Easy using fly antennal cDNA as template and validated by sequencing.  Atf3 in situ probe was generated by cloning ~800 bp atf3 CDS using cDNA template isolated from the antenna of 4000 wild type flies devoid of head and body.
The antibodies used were anti-nc82 (1:50, DHSB ), rabbit anti-GFP (1:1000, Molecular probes commercial antibody) and Goat anti-rabbit Alexa488 (1:100 green Molecular probes)

### Fly stocks:
Pebbled-GAL4 OR promoter fusion lines were kind gift from Alenius Mattias. Atf3 related lines namely Atf3 mutant (yw,atf3(76)/FM7i,P {ActGFP}JMR3),  the Atf3 UAS line (w;UAS-atf3WT/cyo) and pBAC [atf3::EGFP]/TM6B were kind gift from Prof. Uhlirova, M.
miRNA lines used were generated from our lab as previously described and RNAi lines were ordered from Drosophila Stock centre ( Bloomington, Indiana) and VDRC.