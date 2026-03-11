### 1. Title
Single-Cell Multiomics Gene Regulatory Landscape of Testicular Aging

### 2. Authors & Correspondence
#### Co-First Authors
Nanhe Lin, Zhiqiang Zhang, Xianshen Sha, Jiahui Yao (These authors contributed equally)

#### Corresponding Authors
- Nanhe Lin: Department of Urology and Andrology, The First Affiliated Hospital, Sun Yat-sen University | Email: linnanheboshi@foxmail.com
- Chengqiang Mo: Department of Urology and Andrology, The First Affiliated Hospital, Sun Yat-sen University | Email: mochengq@mail.sysu.edu.cn
- Bin Ouyang: Center for Reproductive Medicine, Guangdong Women and Children Hospital | Email: oyb99ol@163.com
- Yun Xie (Lead contact): Department of Urology and Andrology, The First Affiliated Hospital, Sun Yat-sen University | Email: xiey236@mail.sysu.edu.cn

### 3. Citation
If you use the code, data, or findings from this study in your research, please cite the original paper:
```
Lin N, Zhang Z, Sha X, Yao J, Sun X, et al. Single-Cell Multiomics Gene Regulatory Landscape Reveals Impaired Spermatogonial Stem Cells Stemness and Macrophage-Driven Inflammaging During Testicular Aging. [Journal, Year, DOI].
```

### 4. Key R Packages
| Package Category          | Package Name and Version           | Core Application                          |
|---------------------------|------------------------------------|-------------------------------------------|
| Core Single-Cell Analysis | Seurat (v5.0.1), Signac (v1.13.0)  | Basic analysis of scRNA-seq/scATAC-seq    |
| Batch Correction/Integration | Harmony (v1.0)               | Removal of batch effects across datasets  |
| Trajectory/Spatial Analysis | Monocle3 (v1.3.1), Cell2location (v0.1.3) | Pseudotime analysis, spatial cell type mapping |
| Differentiation Potential Analysis | CytoTRACE                  | Cell differentiation potential scoring    |
| Regulatory/Enrichment Analysis | chromVAR, JASPAR2020, clusterProfiler | TF motif analysis, functional enrichment |
| Species Annotation        | org.Mm.eg.db                       | Mouse gene annotation                     |
| Visualization             | ggplot2, ComplexHeatmap, circlize, ggspatial | Plotting (UMAP/Heatmap/Spatial plots)    |

### 5. Key Python Packages
| Package Category          | Package Name and Version           | Core Application                          |
|---------------------------|------------------------------------|-------------------------------------------|
| Regulatory Network Analysis | pySCENIC (v0.11.0), Celloracle (v0.10.12) | Regulon inference, in silico TF perturbation analysis |
| Data Processing           | pandas, numpy, scipy               | Numerical calculation, dataframe processing |
| Visualization             | matplotlib, seaborn                | Statistical plot generation               |
| Single-Cell Analysis      | scanpy, anndata                    | Single-cell data structure management and analysis |

### 6. R/Python Scripts (Updating)
- [x] import_spatial_scRNA_preproced_data
- [ ] cell_clustering_annotation 
- [ ] differential_expression_analysis
- [ ] differential_accessibility_analysis
- [ ] grn_inference_pyscenic
- [ ] pseudotime_trajectory_analysis
- [ ] tf_motif_activity_analysis
- [ ] scRNA_seq_preprocessing
- [ ] scATAC_seq_preprocessing
- [ ] spatial_transcriptomics_analysis
- [ ] core_visualization_plots

### 7. License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
- Permissions: Academic use, modification, and distribution (with proper attribution).
- Restrictions: Commercial use is prohibited without written permission from the corresponding authors.
- Liability: The authors are not liable for any errors or damages arising from the use of this code.

