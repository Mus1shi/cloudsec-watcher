# Architecture

Objectif : scanner Azure, détecter, normaliser, reporter.

```mermaid
flowchart LR
  A[Azure APIs] --> B[scanner]
  B --> C[detectors]
  C --> D[alerts normalizer]
  D --> E[report generator]
