# ai-Gene X™ 🧬

<table>
  <tr>
    <td width="60%" valign="top">
      <strong>ai-Gene X™</strong><br>
      AI-powered genomic analysis platform that allows users to upload raw DNA data (VCF files) and receive personalized genetic insights. Built as a full-stack cloud application, ai-Gene X™ combines bioinformatics, machine learning, and secure data handling to deliver health, ancestry, and trait reports, along with AI-based gene type matching. 
Unlike traditional personality tests such as MBTI, ai-Gene X™ leverages **accurate personal genetic data** to infer individual personality traits, offering a **data-driven, science-backed view of your innate tendencies**.
    </td>
    <td width="40%" valign="top">
      <img src="/introduction_aigenex.png" alt="Dashboard" width="300">
    </td>
  </tr>
</table>

---

## 🚀 Features

### 1. Upload Your DNA (VCF) File
- Supports raw VCF files from 23andMe, AncestryDNA, MyHeritage, and other services.
- Secure upload and optional automatic deletion after analysis.
- Drag & drop or browse file selection.
  <p align="center">
  <img src="/upload_vcf.png" alt="Dashboard" width="1000">
</p>

### 2. AI-Powered Genetic Reports
- Health markers: Trait and disease risk analysis.
- Carrier status: Detect potential carrier conditions.
- Ancestry breakdown: Estimate regional origin from genetic data.
- Physical traits: Predict eye color, height potential, metabolism, and more.
- Gene type matching: Compare your genetic tendencies to famous individuals.

### 3. Share Your DNA Match Card
- Beautifully designed cards summarizing your gene type match.
- Easy to download and share on social media.
- Only trait-level data used—personal DNA remains private.
    <p align="center">
  <img src="/my_dna_variant_card.png" alt="Dashboard" width="1000">
</p>

### 4. Privacy & Security
- Files are encrypted at rest and in transit.
- User-controlled file deletion after processing.
- No third-party data sharing.

### 5. Future Capabilities
- Support for FASTQ and raw sequencing data.
- Polygenic risk scoring and complex disease modeling.
- Family and group trait comparison.
- Clinical report mode for hospital integration.
- Expansion into genomics for animals and plants.

---

## 🖥️ Tech Stack
- **Frontend:** Jinja2 templates, Bootstrap 5
- **Backend:** Flask, Python
- **Database:** SQLAlchemy ORM
- **AI/ML:** Custom variant analysis and gene type prediction
- **Security:** Encrypted file storage, GDPR-compliant data handling

---

## 📷 Screenshots
1. **Genetics Dashboard** – Interactive overview of detected variants and famous personality matches.
   ![Dashboard](/genetics_dashboard.png)
3. **Gene Type & Subcategories** – Manage gene types and detailed trait categories.
   ![Gene Type](/gene_type.png) 
5. **Variant Feature Management** – Annotate variants with effects and scientific references.
   ![Variant Features](/variant_feature.png)
6. **GeneType RSIDs Mapping** – Visualize SNP mapping for AI-based genetic classification.
   ![RSIDs Mapping](/genetype_rsids.png) 
8. **Gene Type Case Management** – Explore curated examples of famous individuals’ gene types.
   ![Gene Type Case Management](/variantfeature-2.png)

---

