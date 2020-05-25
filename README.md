# Alfentanil-Model
Whole-body PBPK model of alfentanil 

<a title="Alfentanil" href="https://commons.wikimedia.org/wiki/File:Alfentanil.svg"><img width="256" alt="Alfentanil" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Alfentanil.svg/256px-Alfentanil.svg.png"></a>

This repository contains:


- a PK-Sim snapshot (*.json) file of the current PBPK model
- static content (e.g. text blocks, *.md files) as inputs for an evaluation plan
- an evaluation plan (evaluation-plan.json) to create an evaluation report using the snapshot and static text blocks to display the performance of the model

**The latest release of the snapshot of the model, the evaluation plan and the static content can be found [here](https://github.com/Open-Systems-Pharmacology/Alfentanil-Model/releases/latest).**

**The latest release of the PK-Sim project model file and the respective evaluation report can be found [here](https://github.com/Open-Systems-Pharmacology/OSP-PBPK-Model-Library/releases/latest).**



This alfentanil model is intended to be used as victim drug in CYP3A4-mediated drug-drug interactions (DDI) as well as for pediatric translations with regard to CYP3A4 ontogeny. 

This  whole-body PBPK model of alfentanil has been developed using in particular published pharmacokinetic clinical data by Ferrier *et al.* 1985 [[1](https://github.com/Open-Systems-Pharmacology/Alfentanil-Model#references)], Kharasch *et al.* 1997 [[2](https://github.com/Open-Systems-Pharmacology/Alfentanil-Model#references)], 2004 [[3](https://github.com/Open-Systems-Pharmacology/Alfentanil-Model#references)], 2011 [[4](https://github.com/Open-Systems-Pharmacology/Alfentanil-Model#references)] , [[5](https://github.com/Open-Systems-Pharmacology/Alfentanil-Model#references)] as well as Meistelmann *et al.* 1987 [[6](https://github.com/Open-Systems-Pharmacology/Alfentanil-Model#references)] and Phimmasone *et al.* 2001 [[7](https://github.com/Open-Systems-Pharmacology/Alfentanil-Model#references)]. The model has then been evaluated simulating a large number of clinical studies and comparing with respective observed data.

The presented model represents an update of the alfentanil model presented by Hanke *et al.* [[8](https://github.com/Open-Systems-Pharmacology/Alfentanil-Model#references)]. Additionally, a decrease in the permeability between the intracellular and  interstitial space  (parameters "P (intracellular->interstitial)" and "P (interstitial->intracellular)") in intestinal mucosa was introduced to optimize  quantitatively the extent of CYP3A4 gut wall metabolism and enable a proper simulation of orally absorbed alfentanil.

## Code of conduct
Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc...) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

## Contribution
We encourage contribution to the Open Systems Pharmacology community. Before getting started please read the [contribution guidelines](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CONTRIBUTING.md#ways-to-contribute). If you are contributing code, please be familiar with the [coding standard](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODING_STANDARDS.md#visual-studio-settings).

## License
The model code is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

## References
[1] [Ferrier, C. et al. Alfentanil pharmacokinetics in patients with cirrhosis. Anesthesiology 62, 480–484 (1985).](https://www.ncbi.nlm.nih.gov/pubmed/3920934)

[2] [Kharasch, E.D. et al. The role of  cytochrome P450 3A4 in alfentanil clearance. Implications for  interindividual variability in disposition and perioperative drug  interactions. Anesthesiology 87, 36–50 (1997).](https://www.ncbi.nlm.nih.gov/pubmed/9232132)

[3]  [Kharasch, E.D., Walker, A., Hoffer, C. & Sheffels, P. Intravenous and oral alfentanil as in vivo probes  for hepatic and first-pass cytochrome P450 3A activity: noninvasive  assessment by use of pupillary miosis. Clin. Pharmacol. Ther. 76, 452–66 (2004).](https://www.ncbi.nlm.nih.gov/pubmed/15536460)

[4] [Kharasch ED, Francis A, London A, Frey K, Kim T, Blood J. Sensitivity of intravenous and oral alfentanil and pupillary miosis as minimal and noninvasive probes for hepatic and first-pass CYP3A induction. Clin Pharmacol Ther. 2011 Jul;90(1):100-8. doi: 10.1038/clpt.2011.59. Epub 2011 May 11. PubMed PMID: 21562488; PubMed Central PMCID: PMC3560934.](https://www.ncbi.nlm.nih.gov/pubmed/21562488)

[5] [Kharasch ED, Vangveravong S, Buck N,  London A, Kim T, Blood J, Mach RH. Concurrent assessment of hepatic and  intestinal cytochrome P450 3A activities using deuterated alfentanil.  Clin Pharmacol Ther. 2011 Apr;89(4):562-70. doi: 10.1038/clpt.2010.313.  Epub 2011 Feb 23.](https://www.ncbi.nlm.nih.gov/pubmed/21346758)

[6] [Meistelman C, Saint-Maurice C, Lepaul M, Levron JC, Loose JP, Mac Gee K. A comparison of alfentanil pharmacokinetics in children and adults. Anesthesiology. 1987 Jan;66(1):13-6. PubMed PMID: 3099603.](https://www.ncbi.nlm.nih.gov/pubmed/3099603)

[7] [Phimmasone, S. & Kharasch, E.D. A pilot evaluation of  alfentanil-induced miosis as a noninvasive probe for hepatic cytochrome  P450 3A4 (CYP3A4) activity in humans. Clin. Pharmacol. Ther. 70, 505–17  (2001).](https://www.ncbi.nlm.nih.gov/pubmed/11753266)

[8] [Hanke N, Frechen S, Moj D, Britz H, Eissing T, Wendl T, Lehr T. PBPK models for CYP3A4 and P-gp DDI prediction: a modeling network of rifampicin, itraconazole, clarithromycin, midazolam, alfentanil and digoxin. CPT: Pharmacometrics & Systems Pharmacology (2018), https://doi.org/10.1002/psp4.12343.](https://ascpt.onlinelibrary.wiley.com/doi/abs/10.1002/psp4.12343) 
