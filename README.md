# Cell-to-Cell Communication: Somatostatin Signaling in Human Pancreatic Islets

## 1. Title and Biological Question

**Student name:**Nesie D. Calipas
**Organism:** *Homo sapiens*  
**Sender cell:** Pancreatic delta cell  
**Candidate ligand:** Somatostatin (SST)  
**Receptor:** Somatostatin receptor 2 (SSTR2)  
**Proposed receiver cell:** Pancreatic alpha cell  

**Biological question:** How can somatostatin released by pancreatic delta cells signal through SSTR2 on pancreatic alpha cells and regulate glucagon secretion?

The purpose of this investigation is to use biological databases and research literature to develop a proposed cell-to-cell communication pathway and distinguish database observations from biological interpretations.

## 2. Chosen Sender Cell and Biological Context

The selected sender cell is the **pancreatic delta cell**, which is found in the islets of Langerhans in the pancreas. Delta cells produce somatostatin, a peptide hormone that helps regulate the secretion of other pancreatic hormones.

The biological context for this project is the regulation of hormone secretion and the maintenance of glucose homeostasis. Somatostatin released by delta cells can act on neighboring pancreatic islet cells and inhibit hormone secretion.

This makes the pancreatic delta cell a biologically relevant sender for investigating communication between cells in the pancreatic islets.

**Supporting resource:** [Human Protein Atlas](https://www.proteinatlas.org/)

## 3. Candidate Ligand and Evidence for Sender-Cell Expression

The candidate ligand is **somatostatin (SST)**, encoded by the *SST* gene. Somatostatin is a peptide hormone produced by pancreatic delta cells.

Information from the Human Protein Atlas indicates that SST expression is enriched in pancreatic islets and other neuroendocrine tissues. This supports the selection of SST as a candidate signal produced by pancreatic delta cells.

Somatostatin can bind to somatostatin receptors, including SSTR2, and regulate hormone secretion. In the proposed pathway, SST is released from the delta cell and acts as an extracellular signaling molecule.

**Supporting resources:**
- [Human Protein Atlas](https://www.proteinatlas.org/)
- [UniProt: Somatostatin (P61278)](https://www.uniprot.org/uniprotkb/P61278/entry)

## 4. Receptor and Receiver Cell with Supporting Evidence

The selected receptor is **somatostatin receptor 2 (SSTR2)**, encoded by the *SSTR2* gene. SSTR2 is a G-protein-coupled receptor that can respond to somatostatin.

The proposed receiver cell is the **pancreatic alpha cell**, which produces glucagon. Research by Kailey et al. (2012) reported SSTR2 expression in human pancreatic alpha and beta cells and identified SSTR2 as a functionally important somatostatin receptor in these cells.

Somatostatin signaling can inhibit glucagon secretion from pancreatic alpha cells. Therefore, the proposed pathway is that SST released by a pancreatic delta cell binds to SSTR2 on a pancreatic alpha cell and contributes to the inhibition of glucagon secretion.

The receptor–receiver relationship is supported by published research. However, this does not independently prove that every delta cell communicates with every alpha cell under all physiological conditions.

**Supporting research:** Kailey, B. et al. (2012), *SSTR2 is the functionally dominant somatostatin receptor in human pancreatic β- and α-cells.*

link: (https://pmc.ncbi.nlm.nih.gov/articles/PMC3492856/)

**Supporting resource:** [UniProt: SSTR2 (P30874)](https://www.uniprot.org/uniprotkb/P30874/entry)

## 5. OmniPath Findings

OmniPath was used to investigate the signaling relationship between somatostatin (SST) and somatostatin receptor 2 (SSTR2). The search result showed an interaction record connecting SST (P61278) to SSTR2 (P30874).

The interaction was labeled **post-translational**, and the record displayed 70 references. The listed source databases included Cellinker, HPRD, LRdb, Guide2Pharma, and connectomeDB2020, among others.

This result supports the biological relevance of the SST–SSTR2 ligand–receptor relationship. In my proposed model, pancreatic delta cells release SST, which can bind to SSTR2 on pancreatic alpha cells. Published research on human pancreatic islets supports the expression of SSTR2 in alpha cells and the inhibitory effect of somatostatin on glucagon secretion.

However, the OmniPath record alone does not demonstrate that the interaction occurs specifically between the selected sender and receiver cells. The proposed cell-to-cell pathway is supported by combining the database result with published evidence about the cells and their functions.

**Resource:** [OmniPath Explorer](https://explore.omnipathdb.org/)

## 6. STRING Network Interpretation

**Resource:** [STRING](https://string-db.org/)

STRING was used to investigate functional protein associations involving SSTR2 and related signaling proteins. The final network contained **11 nodes and 38 edges**, with an average node degree of 6.91. The protein–protein interaction (PPI) enrichment p-value was **1.87 × 10⁻⁸**, indicating that the network contains more interactions than expected for a random set of proteins.

**Receptor-centered network:** The 11 proteins shown in the STRING network were:

- SSTR2
- SST
- GNAI1
- GNAI2
- GNAI3
- GNB1
- GNG2
- NPY
- CORT
- GHRL
- HIVEP2

**Relevant proteins connecting receptor signaling to the cellular response:**

1. **SSTR2:** The receptor that responds to somatostatin.
2. **GNAI1:** An inhibitory G-protein alpha subunit associated with GPCR signaling.
3. **GNAI2:** An inhibitory G-protein alpha subunit involved in intracellular signaling.
4. **GNAI3:** Another inhibitory G-protein alpha subunit associated with GPCR signaling.
5. **GNB1:** A G-protein beta subunit involved in G-protein signaling.

These proteins are relevant to interpreting how receptor activation may influence intracellular signaling. GNG2 is also present in the network and is a G-protein gamma subunit.

**Enriched pathways and biological processes:** The STRING functional enrichment visualization included the following terms:

- Somatostatin signaling pathway
- G protein-coupled receptor signaling pathway
- Adenylate cyclase-inhibiting G protein-coupled receptor signaling pathway
- Adenylate cyclase-modulating G protein-coupled receptor signaling pathway

These enriched terms are consistent with the proposed role of SSTR2 in inhibitory GPCR signaling.

The network supports the biological relevance of these signaling proteins, but STRING associations do not automatically demonstrate direct physical binding, the direction of signaling, or cell-specific activity. The proposed inhibition of glucagon secretion is supported by the combination of network information and published research.

## 7. IntAct Validation

The SST–SSTR2 protein pair was examined as a biologically relevant ligand–receptor relationship. The interaction information available during this investigation showed SST (P61278) and SSTR2 (P30874), with references to multiple publications.

The record included publication identifiers such as PMID 1346068, PMID 7988476, PMID 8702767, PMID 8769372, and PMID 9650799, among others.

These references provide literature context for the reported relationship. However, the interaction type and reference list alone are not enough to identify the exact experimental detection method, the assay conditions, or whether a particular record demonstrates direct physical binding. The experimental method and organism should be recorded from the detailed IntAct record before making a stronger conclusion.

The ligand–receptor relationship is biologically plausible and is supported by published research on somatostatin receptors. Nevertheless, database evidence should be interpreted alongside the original research and the specific experimental evidence reported.

**Resource:** [IntAct Molecular Interaction Database](https://www.ebi.ac.uk/intact/)

## 8. Final Cell-to-Cell Communication Model

The proposed pathway is:

**Pancreatic delta cell → SST → extracellular space → SSTR2 on pancreatic alpha cell → inhibitory G-protein signaling → reduced glucagon secretion**

The proposed intracellular signaling components include SSTR2 and inhibitory G-protein subunits such as GNAI1, GNAI2, and GNAI3. GNB1 is also included as a relevant G-protein signaling component.

### Interpretation of the Final Model

The proposed model describes how pancreatic delta cells may regulate pancreatic alpha cells through somatostatin signaling. Evidence from the Human Protein Atlas supports the association of SST expression with pancreatic islets, making SST a reasonable candidate ligand produced by delta cells. The OmniPath search showed an interaction record linking SST (P61278) to SSTR2 (P30874), supporting the relevance of this ligand–receptor pair. Published research by Kailey et al. (2012) also supports SSTR2 expression in human pancreatic alpha cells and the role of somatostatin in inhibiting hormone secretion.

The STRING network contained 11 proteins and 38 edges, with significant PPI enrichment. Its enriched terms included the somatostatin signaling pathway and inhibitory G-protein-coupled receptor signaling. GNAI1, GNAI2, GNAI3, and GNB1 are relevant components for interpreting receptor-associated signaling. The expected response is reduced glucagon secretion from the alpha cell.

Although the database findings and research support the biological plausibility of this model, they do not independently prove that the complete pathway occurs between the selected cells in every physiological condition. The exact intracellular steps and the degree of inhibition remain interpretations of the combined evidence.

## 9. References and Database Links

1. **Human Protein Atlas.** Protein and tissue expression information. https://www.proteinatlas.org/
2. **OmniPath.** Intercellular and intracellular signaling knowledge. https://explore.omnipathdb.org/
3. **STRING.** Functional protein association networks and enrichment analysis. https://string-db.org/
4. **IntAct.** Molecular interaction database. https://www.ebi.ac.uk/intact/
5. **UniProt: Somatostatin (P61278).** https://www.uniprot.org/uniprotkb/P61278/entry
6. **UniProt: Somatostatin receptor 2 (P30874).** https://www.uniprot.org/uniprotkb/P30874/entry
7. **Kailey, B. et al. (2012).** *SSTR2 is the functionally dominant somatostatin receptor in human pancreatic β- and α-cells.* https://pmc.ncbi.nlm.nih.gov/articles/PMC3492856/

---

# 10. Questions to Answer 

### 1. What sender cell did you choose, and in what tissue or biological context does it act?

I chose the pancreatic delta cell, which is found in the islets of Langerhans in the pancreas. It acts in the regulation of pancreatic hormone secretion and glucose homeostasis by releasing somatostatin, which can inhibit hormone secretion from neighboring islet cells.

### 2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?

The signaling molecule I identified is somatostatin (SST), encoded by the *SST* gene. The Human Protein Atlas reports SST expression enriched in pancreatic islets, supporting its association with the pancreatic delta cell. Somatostatin is also an established peptide hormone produced by delta cells.

### 3. What receptor receives the signal, and which receiver cell did you select?

The receptor is somatostatin receptor 2 (SSTR2), and the proposed receiver cell is the pancreatic alpha cell. Kailey et al. (2012) reported SSTR2 expression in human pancreatic alpha cells and described its functional importance in somatostatin signaling.

### 4. What type of cell-to-cell signaling is represented: paracrine, endocrine, autocrine, or contact-dependent?

The proposed communication is **paracrine signaling**, because somatostatin released by a pancreatic delta cell can act on nearby pancreatic alpha cells within the islets. Somatostatin can also have endocrine effects in other contexts, but the selected local delta-cell-to-alpha-cell model is most consistent with paracrine signaling.

### 5. Which proteins in your STRING network appear most relevant to the receptor-associated response? Explain briefly.

The most relevant proteins are SSTR2, GNAI1, GNAI2, GNAI3, and GNB1. SSTR2 receives the somatostatin signal, while GNAI1, GNAI2, and GNAI3 are inhibitory G-protein alpha subunits associated with GPCR signaling. GNB1 is a G-protein beta subunit that participates in intracellular signal transmission. These proteins help explain how SSTR2 activation may influence the activity of the receiver cell. The proposed response is reduced glucagon secretion, consistent with published research on somatostatin signaling in pancreatic alpha cells.

### 6. What enriched pathway or biological process is consistent with your proposed mechanism?

The STRING enrichment results included the somatostatin signaling pathway, G protein-coupled receptor signaling pathway, and adenylate cyclase-inhibiting G protein-coupled receptor signaling pathway. These terms are consistent with the proposed inhibitory signaling role of SSTR2.

### 7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?

The SST–SSTR2 pair was examined, and interaction information linking SST (P61278) and SSTR2 (P30874) was found in the interaction resources investigated. The displayed record listed several publication references. However, I have not confirmed the exact experimental detection method and assay details from the IntAct record. Therefore, I cannot conclude from the reference list alone that the record demonstrates direct physical binding. The detailed IntAct method and organism fields should be checked before making that claim.

### 8. Which parts of your final model are strongly supported, and which parts remain an inference?

The identity of SST as a somatostatin ligand, the association of SSTR2 with somatostatin signaling, the expression of SSTR2 in human pancreatic alpha cells, and the inhibitory effect of somatostatin on alpha-cell hormone secretion are supported by database information and published research. The STRING network and its enrichment terms also support the relevance of GPCR and inhibitory G-protein signaling.

However, the complete pathway from the particular delta cell to the particular alpha cell, the exact intracellular sequence in that cell, and the size of the resulting glucagon reduction remain inferences. The database records do not independently demonstrate that the entire pathway is active under every physiological condition.

### 9. What cellular response is expected in the receiver cell, and why?

The expected response is inhibition of glucagon secretion by the pancreatic alpha cell. Somatostatin released from the delta cell can bind to SSTR2 on the alpha cell and activate inhibitory signaling. Published research supports the role of SSTR2 in somatostatin-mediated regulation of hormone secretion in human pancreatic islets.

