# Identification of a gene expression signature associated with Breast Cancer survival and risk that improves clinical genomic platforms
[Santiago Bueno-Fortes](https://scholar.google.com/scholar?q=author:%22Bueno-Fortes%20Santiago%22), [Alberto Berral-Gonzalez](https://scholar.google.com/scholar?q=author:%22Berral-Gonz%C3%A1lez%20Alberto%22), [José Manuel Sánchez-Santos](https://scholar.google.com/scholar?q=author:%22S%C3%A1nchez-Santos%20Jos%C3%A9%20Manuel%22), [Manuel Martin-Merino](https://scholar.google.com/scholar?q=author:%22Merino%20Manuel%20Mart%C3%ADn%22), [Javier De Las Rivas](https://scholar.google.com/scholar?q=author:%22De%20Las%20Rivas%20Javier%22)

_Bioinformatics Advances_, vbad037, [https://doi.org/10.1093/bioadv/vbad037](https://doi.org/10.1093/bioadv/vbad037)

**Published**: 22 March 2023

## Motivation

Modern genomic technologies allow us to perform genome-wide analysis to find gene markers associated with the risk and survival in cancer patients. Accurate risk prediction and patient stratification based on robust gene signatures is a key path forward in personalized treatment and precision medicine. Several authors have proposed the identification of gene signatures to assign risk in patients with breast cancer (BRCA), and some of these signatures have been implemented within commercial platforms in the clinic, such as Oncotype and Prosigna. However, these platforms are black boxes in which the influence of selected genes as survival markers is unclear and where the risk scores provided can not be clearly related to the standard clinico-pathological tumor markers obtained by immunohistochemistry (IHC), which guide clinical and therapeutic decisions in breast cancer.

## Results

Here we present a framework to discover a robust list of gene expression markers associated with survival that can be biologically interpreted in terms of the 3 main biomolecular factors (IHC clinical markers: ER, PR and HER2) that define clinical outcome in BRCA. To test and ensure the reproducibility of the results, we compiled and analyzed two independent datasets with a large number of tumor samples (1,024 and 879) that include full genome-wide expression profiles and survival data. Using these two cohorts, we obtained a robust subset of gene survival markers that correlate well with the major IHC clinical markers used in breast cancer. The geneset of survival markers that we identify (which includes 34 genes) significantly improves the risk prediction provided by the genesets included in the commercial platforms: Oncotype (16 genes) and Prosigna (50 genes, i.e. PAM50). Furthermore, some of the genes identified have recently been proposed in the literature as new prognostic markers and may deserve more attention in current clinical trials to improve breast cancer risk prediction.

## Availability

All data integrated and analyzed in this research will be available on this [GitHub](https://github.com/jdelasrivas-lab/breastcancersurvsign), including the R scripts and protocols used for the analyses.

## Supplementary information

[Supplementary material](https://oup.silverchair-cdn.com/oup/backfile/Content_public/Journal/bioinformaticsadvances/PAP/10.1093_bioadv_vbad037/1/vbad037_supplementary_data.pdf?Expires=1682740047&Signature=IGQ4hIZry5tslpkKfEnc49Wy2CCwmmiJtVM2QPKQLi~DyEB6KYCsDhfiZ1L9O~T6vvoNedMZqVhr059DEYqPpT6TeTq-7H9VBwRxcHHO5VmQYlHre-aCJp~Wz-nlwLZVXnBfdL9KSPOTy-rMDuxNi2-I6fbhk3V~7J~XQ80VvTPWfPiDfHX3GmLwTIFelbSO~p31FCJrKwBTw1r8SNxujbv0sR7~8BjlqZSjIVKcTJBRTBs~5WNY6C-WifMBXVWXbXUvhjVLQ8CjUfZ~sK2nHe9yYo1v-M7c8vja6a4RwRuu8CiCD35IKZyqjmxG7iD-zHuxSbDsnA~K3UNKow5TBA__&Key-Pair-Id=APKAIE5G5CRDK6RD3PGA) is available at _Bioinformatics Advances_ online.
