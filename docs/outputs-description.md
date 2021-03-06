---
description: Here are the various outputs of the workflow
---

# Outputs Description

If you run the workflow with default settings, these following files are expected:

| File Name | File Description |
| :--- | :--- |
| `<READ1_FASTQ_BASENAME>_val_1_srt_md_abra_fm_bqsr.bam` | Final binary alignment map \(BAM\) file generated by the process |
| `<READ1_FASTQ_BASENAME>_val_1_srt_md_abra_fm_bqsr.bai` | The binary alignment index \(BAI\) file associated with the final bam.  |
| `<READ1_FASTQ_FILENAME>_trimming_report.txt` | READ1 trimming metrics from trim\_galore |
| `<READ2_FASTQ_FILENAME>_trimming_report.txt` | READ2 trimming metrics from trim\_galore |
| `<READ1_FASTQ_BASENAME>_val_1_srt_md.bam` | Mark Duplicates Binary Alignment Map file generated after Picard MarkDuplicates. |
| `<READ1_FASTQ_BASENAME>_val_1_srt_md.bai` | The binary alignment index \(BAI\) file associated with the Mark Duplicated bam file |
| `<READ1_FASTQ_BASENAME>_val_1_srt_md.metrics` | Metrics file for MarkDuplicated bam file. |

Where:

* **&lt;READ1\_FASTQ\_BASENAME&gt;** refers to the Read 1 fastq basename \(w/o extension\)
  * Ex: SAMPLE\_R1\_001
* **&lt;READ1\_FASTQ\_FILENAME&gt;** refers to the Read 1 fastq filename 
  * Ex: SAMPLE\_R1\_001.fastq.gz
* **&lt;READ2\_FASTQ\_FILENAME&gt;** refers to the Read 2 fastq filename 
  * Ex: SAMPLE\_R2\_001.fastq.gz



