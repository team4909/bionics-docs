---
title: How Parts are Made
---

{{< mermaid >}}
graph TD
    A(Concept) --> B(Design Intent)
    B --> C(Design: CAD/Drawings)
    C --> D(CAM)
    D --> E(CNC Machine)
    E --> F[Final Part]

    C --> 1(Manual Operations)
    1 --> F
{{< /mermaid >}}