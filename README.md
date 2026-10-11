# idslibrary

A catalogue of real IDS files published by building and infrastructure owners, public bodies and standards groups.

An IDS file (Information Delivery Specification, a buildingSMART standard) lists the information a building model must contain, in a form software can check. For example: every wall has a fire rating. Owners publish IDS files so that the models delivered to them can be checked the same way by everyone.

This catalogue tells you who publishes such files, what they cover, where to get them from the publisher, and on what terms. It links to the publisher's own page. It does not copy their files.

## Sources

| Publisher | Country | Sector | What it is | Files | IDS version | Language | Terms for reuse | Where to get it |
|---|---|---|---|---|---|---|---|---|
| Bane NOR | Norway | Rail | KIM 1.1.0, information requirements for development projects, by delivery stage and discipline (published January 2026) | 54 | 1.0 | Norwegian | None stated on the page | [banenor.no, KIM project](https://www.banenor.no/leverandor/krav-og-sikkerhet/regler-og-arbeidsprosesser/bim-og-standardisering-i-jernbaneinfrastruktur/kim-prosjektet-strukturering-og-standardisering-av-informasjonsleveranser-i-utbyggingsprosjekter/) |
| Statsbygg | Norway | Public buildings | SIMBA 2.1 requirement sets, by stage and discipline. Labelled experimental by the publisher | 48 | 0.9.6 | English | None stated on the page | [simba.statsbygg.no](https://simba.statsbygg.no/kravene/maskinvalid%C3%A9rbare-krav) |
| Department for Education | United Kingdom | School buildings | Information model assurance checks for RIBA stages 3, 4 and 5 | 1,868 | 1.0 | English | CC BY 4.0 | [GitHub: DFE-EducationEstates/InformationModelAssurance](https://github.com/DFE-EducationEstates/InformationModelAssurance) |
| TU Wien, for the City of Vienna | Austria | Building permits | Checks of the OIB 2 building code for permit models (research data) | 16 | 1.0, some with extensions | English | CC BY 4.0 | [TU Wien research data, record 1](https://researchdata.tuwien.ac.at/doi/10.48436/krhhx-xyz91), [record 2](https://researchdata.tuwien.at/records/yh1wr-8t679) |
| buildingSMART Portugal | Portugal | Private and public works | Exchange information requirements for the design stage, by discipline | 12 | 1.0 | Portuguese and English | MIT | [GitHub: private works](https://github.com/buildingSMART-Portugal/EIR-FaseProjeto-ObraPrivada), [public works](https://github.com/buildingSMART-Portugal/EIR-FaseProjeto-ObraPublica) |
| buildingSMART International | International | Examples | Example IDS files that accompany the standard | 12 | 1.0 | English, Dutch | CC BY-ND 4.0, unchanged copies only | [GitHub: buildingSMART/IDS](https://github.com/buildingSMART/IDS), folder `Documentation/Examples` |

Counts, versions and terms are as found on 11 October 2026. Publishers change their pages: follow the link for the current state, and tell us when a row is out of date.

## How to read "Terms for reuse"

- **A named licence** (for example CC BY 4.0) means the publisher allows copying and reuse under that licence. Read the licence before you redistribute.
- **None stated** means the publisher has made the files available to download but has not said that others may republish them. You can download and use them for the publisher's projects as they intend. Ask the publisher before copying them elsewhere.

This is why the catalogue links to each publisher and holds no copies. Files will be mirrored here only where the licence clearly allows it, or the publisher has agreed in writing.

## What is planned

- A check result for each file (does it follow the IDS 1.0 standard), produced with [idsbench](https://github.com/BIMvoice/idsbench) and the official buildingSMART audit tool. Results are shared with each publisher before they appear here.
- Mirrored copies of the sets whose licence allows it, with credit.
- More publishers. If your organisation publishes IDS files, or you know one that does, open an issue with the link.

## Using a file from the catalogue

1. Download the file from the publisher's page.
2. Open it in [idsbench](https://github.com/BIMvoice/idsbench) or another IDS tool to read it, check it, and run it against an IFC model.

idsbench works with IDS 1.0. Files in older versions need to be updated by their publisher first.

## The catalogue as data

[`catalogue.json`](catalogue.json) holds the same rows in a form tools can read.

## Licence

The catalogue text and `catalogue.json` are licensed under [CC BY 4.0](LICENSE). The IDS files themselves belong to their publishers and are covered by each publisher's own terms.

Maintained by [BIMvoice](https://bimvoice.com).
