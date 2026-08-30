+++
title = "About"
date = '2022-04-09T07:15:00+07:00'
slug = "about"
draft = false
+++

## Research network

{{< network >}}
flowchart LR
    Me["Me"] --> DryLab["Dry lab"]
    Me["Me"] --> WetLab["Wet lab"]

    WetLab --> Culture["Culture cells"]
    Culture --> LLCMK2["LLCMK2"]
    Culture --> Macrophages["Macrophages"]
    Culture --> BoneMarrow["Bone marrow"]
    Culture --> Tcruzi["Trypanosoma cruzi"]

    WetLab --> Molecular["Molecular biology"]
    Molecular --> qPCR["qPCR"]
    Molecular --> RT["RT"]

    DryLab --> ML["Machine learning"]
    DryLab --> Bulk["Bulk sequencing"]
    DryLab --> SingleCell["Single-cell sequencing"]
    DryLab --> Integrative["Integrative analysis"]
{{< /network >}}