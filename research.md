<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Research Experience | Tahmineh Mehrabi</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      background: #f6f8fb;
      color: #243247;
      font-family: Arial, sans-serif;
      line-height: 1.7;
    }

    main {
      max-width: 960px;
      margin: 0 auto;
      padding: 48px 24px;
    }

    h1 {
      margin-bottom: 8px;
      color: #162c46;
    }

    .intro {
      margin-top: 0;
      color: #58677a;
    }

    .experience-item {
      margin-top: 28px;
      padding: 28px;
      background: #ffffff;
      border: 1px solid #e0e6ed;
      border-radius: 12px;
    }

    .experience-header {
      display: flex;
      align-items: flex-start;
      justify-content: space-between;
      gap: 16px;
    }

    .experience-role {
      margin: 0;
      color: #162c46;
      font-size: 20px;
      line-height: 1.4;
    }

    .experience-date {
      flex-shrink: 0;
      color: #087f8c;
      font-size: 14px;
      font-weight: bold;
    }

    .experience-organization {
      margin: 14px 0 8px;
      font-weight: bold;
    }

    .experience-meta {
      margin: 8px 0;
      color: #58677a;
    }

    a {
      color: #087f8c;
      text-underline-offset: 3px;
    }

    a:hover {
      color: #055762;
    }

    .experience-details {
      margin-bottom: 0;
      padding-left: 22px;
    }

    .experience-details li {
      margin-bottom: 12px;
    }

    @media (max-width: 600px) {
      main {
        padding: 28px 16px;
      }

      .experience-item {
        padding: 20px;
      }

      .experience-header {
        flex-direction: column;
        gap: 8px;
      }
    }
  </style>
</head>

<body>
  <main>
    <h1>Research Experience</h1>
    <p class="intro">
      Tahmineh Mehrabi — Cancer Transcriptomics Researcher
    </p>

    <!-- Lung Adenocarcinoma -->
    <article class="experience-item">
      <div class="experience-header">
        <h4 class="experience-role">
          Integrated Transcriptomic Analysis of Lung Adenocarcinoma
        </h4>
        <span class="experience-date">In Progress</span>
      </div>

      <p class="experience-organization">
        Research Collaborator — Bulk, Single-Cell &amp; Spatial Transcriptomics
      </p>

      <p class="experience-meta">
        <a href="https://github.com/tahminehmehrabii/LUAD"
           target="_blank"
           rel="noopener noreferrer">
          GitHub Repository
        </a>
      </p>

      <ul class="experience-details">
        <li>
          Analyzed bulk RNA-seq data to identify glycolysis-related
          genes associated with survival; developed a nine-gene
          LASSO–Cox prognostic model and evaluated risk-group survival
          differences in an independent dataset.
        </li>
        <li>
          Applied Seurat workflows for single-cell quality control,
          normalization, clustering, and cell-type annotation;
          examined GPR87 expression in malignant and non-malignant
          cell populations.
        </li>
        <li>
          Analyzed Visium data from 56 tissue sections across
          25 patients and mapped GPR87 expression onto H&amp;E images;
          used ssGSEA and Spearman correlation to identify a stronger
          association with glycolysis than with immune-signature scores.
        </li>
      </ul>
    </article>

    <!-- Colorectal Cancer -->
    <article class="experience-item">
      <div class="experience-header">
        <h4 class="experience-role">
          Single-Cell and Spatial Transcriptomic Analysis of
          Colorectal Cancer and Host–Bacteria Associations
        </h4>
        <span class="experience-date">In Progress</span>
      </div>

      <p class="experience-organization">
        Research Collaborator — Single-Cell &amp; Spatial Transcriptomics
      </p>

      <p class="experience-meta">
        <a href="https://github.com/tahminehmehrabii/CRC-SingleCell-Spatial-Analysis"
           target="_blank"
           rel="noopener noreferrer">
          GitHub Repository
        </a>
      </p>

      <ul class="experience-details">
        <li>
          Developed Seurat workflows for 10 matched tumor–normal
          patient pairs, including quality control, normalization,
          clustering, cell-type annotation, and paired cell-type
          and subtype composition analysis.
        </li>
        <li>
          Applied RCTD deconvolution to four spatial sections from
          two matched patient pairs, separating host and bacterial
          signals and mapping cell-type proportions and selected
          host features.
        </li>
        <li>
          Investigated spatial associations of bacterial signals
          with myeloid, epithelial-signature, and EPCAM features;
          characterized paired tumor–normal changes across
          19 bacterial groups and exploratory bacterial spatial
          co-occurrence.
        </li>
      </ul>
    </article>

    <!-- Laryngeal Squamous Cell Carcinoma -->
    <article class="experience-item">
      <div class="experience-header">
        <h4 class="experience-role">
          MYBL2 Biomarker Discovery in Laryngeal Squamous Cell
          Carcinoma (LSCC)
        </h4>
      </div>

      <p class="experience-organization">
        Research Collaborator — Cancer Transcriptomics and Machine Learning
      </p>

      <p class="experience-meta">
        <a href="https://github.com/tahminehmehrabii/LSCC-MYBL2-Biomarker"
           target="_blank"
           rel="noopener noreferrer">
          GitHub Repository
        </a>
      </p>

      <ul class="experience-details">
        <li>
          Integrated public bulk and single-cell RNA-seq datasets
          to investigate MYBL2 as a candidate transcriptomic
          biomarker in LSCC.
        </li>
        <li>
          Applied differential expression analysis, WGCNA,
          inferCNV and LASSO to assess transcriptional signatures
          and malignant epithelial populations.
        </li>
        <li>
          Evaluated biomarker models using Random Forest and SVM
          alongside external transcriptomic validation;
          investigated enrichment, immune associations, pseudotime
          and cell–cell communication using CellChat.
        </li>
      </ul>
    </article>

    <!-- Master's Thesis -->
    <article class="experience-item">
      <div class="experience-header">
        <h4 class="experience-role">
          EMT-Associated lncRNA Signatures in Castration-Resistant
          Prostate Cancer (CRPC)
        </h4>
      </div>

      <p class="experience-organization">
        Graduate Researcher — Cancer Bioinformatics
      </p>

      <p class="experience-meta">
        Azad University, Tehran Medical Sciences
        &middot; Supervisor: Masoumeh Heshmati, Ph.D.
      </p>

      <p class="experience-meta">
        Thesis: EMT-associated lncRNA signatures in
        castration-resistant prostate cancer (CRPC)
      </p>

      <p class="experience-meta">
        <a href="https://github.com/tahminehmehrabii/CRPC-lncRNA-WGCNA-Analysis-of-GSE74685"
           target="_blank"
           rel="noopener noreferrer">
          GitHub Repository
        </a>
      </p>

      <ul class="experience-details">
        <li>
          Processed and analyzed the public dataset GSE74685
          in R, including annotation, normalization and
          differential expression analysis.
        </li>
        <li>
          Combined WGCNA, GO/KEGG enrichment and interpretation
          of expression networks to prioritize TP53TG1, RFPL1S,
          DLEU1 and HCG4 as candidate EMT-associated lncRNAs.
        </li>
      </ul>
    </article>
  </main>
</body>
</html>
