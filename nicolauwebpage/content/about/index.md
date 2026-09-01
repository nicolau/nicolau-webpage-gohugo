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
    Me --> WetLab["Wet lab"]

    DryLab --> ML["Machine learning"]
    DryLab --> Bulk["Bulk sequencing"]
    DryLab --> SingleCell["Single-cell sequencing"]
    DryLab --> Integrative["Integrative analysis"]

    WetLab --> Molecular["Molecular biology"]
    Molecular --> qPCR["qPCR"]
    Molecular --> RT["RT"]

    WetLab --> Culture["Culture cells"]
    Culture --> LLCMK2["LLCMK2"]
    Culture --> Macrophages["Macrophages"]
    Culture --> BoneMarrow["Bone marrow"]
    Culture --> Tcruzi["Trypanosoma cruzi"]

    click Me "/about/" "About me"
    click DryLab "/projects/" "Dry-lab projects"
    click WetLab "/projects/" "Wet-lab projects"
    click Culture "/projects/cell-culture/" "Cell culture project"
    click Molecular "https://en.wikipedia.org/wiki/Molecular_biology" "Molecular biology"

    classDef person fill:#7c3aed,color:#ffffff,stroke:#5b21b6
    classDef wet fill:#16a34a,color:#ffffff,stroke:#166534
    classDef dry fill:#ea580c,color:#ffffff,stroke:#9a3412
    classDef technique fill:#2563eb,color:#ffffff,stroke:#1e40af

    class Me person
    class WetLab,Culture,Molecular,LLCMK2,Macrophages wet
    class DryLab dry
    class qPCR technique
{{< /network >}}
