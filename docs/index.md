![bcbio banner](contents/images/banner.png)

A python toolkit providing best-practice pipelines for fully automated
high throughput sequencing analysis. You write a high level configuration file
specifying your inputs and analysis parameters. This input drives a parallel pipeline
that handles distributed execution, idempotent processing restarts and safe transactional steps.
The goal is to provide a shared community resource that handles
the data processing component of sequencing analysis, providing researchers with more time to focus on the downstream biology.

# Contents

```{toctree}
---
maxdepth: 2
---
contents/intro.md
```

```{toctree}
---
maxdepth: 2
caption: User stories
---
contents/somatic_variants.md
contents/bulk_rnaseq.md
contents/single_cell.md
contents/purecn.md
contents/hla_typing.md
contents/germline_variants.md
contents/3prime_dge.md
contents/structural_variants.md
contents/atac.md
contents/methylation.md
contents/rnaseq_variants.md
contents/rnaseq_fusions.md
contents/fast_rnaseq.md
contents/disambiguation.md
contents/small_rnaseq.md
```

```{toctree}
---
maxdepth: 2
caption: Infrastructure
---
contents/installation.md
contents/configuration.md
contents/parallel.md
contents/outputs.md
contents/cwl.md
contents/cloud.md
contents/development.md
```

```{toctree}
---
maxdepth: 2
caption: Misc
---
contents/users.md
contents/internals.md
contents/presentations.md
contents/teaching.md
contents/citations.md
```
