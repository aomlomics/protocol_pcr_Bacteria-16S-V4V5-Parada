---
# MIOP terms
methodology_category: omics analysis
project: "NOAA Atlantic Oceanographic and Meteorological Laboratory Omics Program; https://github.com/aomlomics/protocols; https://zenodo.org/communities/aomlomics"
purpose: amplicon sequencing assay [OBI:0002767] | polymerase chain reaction assay [OBI:0002692]
analyses: amplicon sequencing assay [OBI:0002767] | polymerase chain reaction assay [OBI:0002692]
geographic_location: Atlantic Ocean [GAZ:00000344], Gulf of Mexico [GAZ:00002853]
broad_scale_environmental_context: marine biome [ENVO:00000447]
local_environmental_context: marine pelagic zone [ENVO:00000208], marine benthic biome [ENVO:01000024]
environmental_medium: seawater [ENVO:01001964]
target: "16S Mitochondrial Ribosomal RNA [NCIT:C131261]"
creator: Luke Thompson, Sean Anderson
materials_required: vortexer [OBI:0400118], PCR instrument [OBI:0000989], agarose gel electrophoresis system [OBI:0001134]
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 240
personnel_required: 1
language: en
issued: 2021-02-08
audience: scientists
publisher: NOAA Atlantic Oceanographic and Meteorological Laboratory
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
pcr_0_1: 1
thermocycler: Eppendorf Mastercycler Nexus Thermal Cycler
amplificationReactionVolume: 25
assay_name: Universal-SSU-V4V5-Parada
assay_validation: not provided
targetTaxonomicAssay: 16S rRNA gene sequencing targeting the V4-V5 region using primers 515F and 926R
targetTaxonomicScope: Prokaryotes, including Bacteria and Archaea
target_gene: 16S rRNA (SSU prokaryote)
target_subfragment: V4-V5
ampliconSize: 411
pcr_primer_forward: GTGYCAGCMGCCGCGGTAA
pcr_primer_reverse: CCGYCAATTYMTTTRAGTTT
pcr_primer_name_forward: 515F-Y
pcr_primer_name_reverse: 926R
pcr_primer_reference_forward: 10.1111/1462-2920.13023
pcr_primer_reference_reverse: 10.1111/1462-2920.13023
pcr_primer_vol_forward: 1.0
pcr_primer_vol_reverse: 1.0
pcr_primer_conc_forward: 10
pcr_primer_conc_reverse: 10
probeReporter: not applicable
probeQuencher: not applicable
probe_seq: not applicable
probe_ref: not applicable
probe_conc: not applicable
commercial_mm: AmpliTaq Gold 360 Master Mix
custom_mm: PCR reactions were run in 25 uL reaction volumes, with 1.0 uL of DNA, 12.5 uL of AmpliTaq Gold, 9.5 uL of water, and 1.0 uL of each primer (10 uM).
pcr_dna_vol: 1.0
pcr_rep: 1
nucl_acid_amp: https://doi.org/10.1111/1462-2920.13023
pcr_cond: initial denaturation:95_3;denaturation:95_0.75;annealing:50_0.75;elongation:72_1.5;final elongation:72_10;30
annealingTemp: 50
pcr_cycles: 30
pcr_analysis_software: not provided
pcr_method_additional: not provided
barcoding_pcr_appr: two-step PCR
pcr2_thermocycler: not provided
pcr2_amplificationReactionVolume: 15
pcr2_commercial_mm: 2X Dream Taq Master Mix (K1920)
pcr2_custom_mm: not applicable
pcr2_dna_vol: 1
pcr2_cond: initial denaturation:95_3;denaturation:95_0.25;annealing:60_0.5;elongation:72_1.5;final elongation:72_3;11
pcr2_annealingTemp: 60
pcr2_cycles: 11
pcr2_analysis_software: not applicable
pcr2_method_additional: not applicable
---

# NOAA/AOML PCR Protocol 16S rRNA V4-V5 (Parada)

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Luke Thompson | NOAA/AOML, MSU/NGI | <https://orcid.org/0000-0002-3911-1280> | 2021-02-28 |
| Sean Anderson | NOAA/AOML, MSU/NGI | <https://orcid.org/0000-0003-3096-1120> | 2021-02-28 |
| Sammy Harding | NOAA/AOML, MSU/NGI | <https://orcid.org/0009-0008-8885-6140> | 2024-08-19 |

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Internal Protocols: Derivative or altered protocols, or other protocols in this workflow.
- External Protocols: Protcols from manufacturers or other groups. 
- Include the link to each protocol.
- Include the version number (internal) or access date (external) of the protocol when it was accessed.

#### Internal Protocols

| PROTOCOL NAME | LINK  | VERSION | RELEASE DATE|
| ------------- | ------------- | ------------- | ------------- |
| AOML 'Omics Protocols | <https://github.com/aomlomics/protocols> | 1.2.2 | ongoing |

#### External Protocols

| PROTOCOL NAME | LINK | ISSUER / AUTHOR | ACCESS DATE |
| ------------ | ------------ | ------------ | ---------- |
| Fuhrman Lab 515F-926R 16s and 18S rrna gene sequencing protocol | dx.doi.org/10.17504/protocols.io.vb7e2rn | Fuhrman, J. et al. | 2025-02-05 |
| AMPure XP Bead-Based Reagent Protocol for PCR Purification | https://www.beckman.com/reagents/genomic/cleanup-and-size-selection/pcr/ampure-xp-protocol | Beckman Coulter | 2025-02-05 |
| Invitrogen Qubit 1X dsDNA HS Assay Kits User Guide | https://assets.thermofisher.com/TFS-Assets/LSG/manuals/MAN0017455_Qubit_1X_dsDNA_HS_Assay_Kit_UG.pdf | Thermo Fisher Scientific | 2025-02-05 |

### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2021-02-28 | Initial release |
| 1.0.1 | 2024-10-23 | Formatting edits |
| 1.1.0 | 2024-11-16 | Addition of FAIR eDNA terms in YAML frontmatter |
| 1.2.0 | 2025-09-18 | Addition of sequencing preparation and Illumina sequencing facility information |
| 1.2.1 | 2025-12-15 | Update YAML front matter |
| 1.2.2 | 2026-01-23 | Renamed assay |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
| NOAA | National Oceanographic and Atmospheric Administration |
| AOML | Atlantic Oceanographic and Meteorological Laboratory |
| MSU | Mississippi State University |
| NGI | Northern Gulf Institute |
| PCR | Polymerase chain reaction |
| eDNA | environmental DNA |
| NTC | No template control |
| EtOH | Ethanol |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Extraction Blank | A type of negative control to confirm there is no contamination during DNA extractions. Normally an empty filter extracted and PCR amplified alongside other samples. |
| No Template Control | A type of negative control during PCR to confirm there is no contamination during the PCR process. Normally nuclease-free water run in place of DNA on a PCR. |

## BACKGROUND

### Summary

This protocol describes steps for performing PCR for [16S rRNA](target_gene) [V4-V5](target_subfragment) marker gene regions using eDNA extracted from Sterivex at NOAA's AOML. There are several optional steps towards the end of the protocol including using AMPure beads to clean up PCR products. The PCR protocol only includes a primary PCR step as the secondary PCR, library preparation and Illumina sequencing is completed by Michigan State University's RTSF Genomics Core. Steps related to preparing samples for sequencing and the Genomics Core's procedure are included. Some steps (e.g. PCR plate preparation) have been or can be optimized for use with the Opentrons OT2 robot. This protocol closely aligns with the following 16S protocol: <https://www.protocols.io/view/fuhrman-lab-515f-926r-16s-and-18s-rrna-gene-sequen-j8nlkpd1g5r7/v2?step=102>.

### Method description and rationale

This protocol is used for PCR amplifying the [16S rRNA](target_gene) [V4-V5](target_subfragment) marker gene regions of environmental DNA. Fluidigm adapter are already present on the primers described in the following protocol. It is highly reproducible and can easily be adapted for any number of samples (i.e. a full 96-well plate or a few samples).

### Spatial coverage and environment(s) of relevance

This protocol can be used to amplify the [16S rRNA](target_gene) marker gene region of any eDNA sample.

## PERSONNEL REQUIRED

One person with molecular biology experience.

### Safety

There are no hazardous chemicals or materials involved in this protocol. Standard lab safety techniques should still be used such as wearing PPE to avoid skin or eye contact.

### Training requirements

Basic molecular biology training is sufficient for this protocol including sterile technique, pipetting small volumes and programming/running PCR thermal cyclers.

### Time needed to execute the procedure

Protocol takes about 4 hours ([240](time_required) minutes) including thermal cycler run time.

## EQUIPMENT

For 96-well Plate:

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
| 100-1000 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 10-100 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 0.1-2.5 ul Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 10-100 ul 8-Channel Pipette | Eppendorf Research Plus 8 Channel Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 0.5-10 uL 8-Channel Pipette |Eppendorf Research Plus 8 Channel Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| Thermal cycler | Mastercycler Nexus Thermal Cycler | Eppendorf | 1 | Can be substituted with generic |
| Microwave | Generic Microwave | Generic Brand | 1 | |
| Flask | 500 mL Flask | Generic Brand | 1 | Used for mixing agarose gel solution |
| 1-L Glass Container | 1 L Glass Container | Generic Brand | 1 | Used for storing 1x TBE buffer |
| Gel Tray & Box | Gel Electrophoresis Box and Tray | Generic Brand | 1 | Can be substituted with generic |
| Gel Combs | Gel Electrophoresis Combs | Generic Brand | 2 | Can be substituted with generic |
| **Consumable equipment** |
| Gloves | Nitrile Gloves, Exam Grade, Powder-free | ULINE | 1 | (box) Can be substituted with generic |
| Kim Wipes | KimWipe Delicate Task Wipers | KimTech | 1 | (box) Can be substituted with generic |
| 96-well PCR Plate | | Armadillo PCR Plate, 96-well, clear, clear wells | ThermoFisher | 3 | |
| PCR Plate Seal | AlumaSeal II Sealing Foils for PCR and Cold Storage | VWR | 2 | Can be substituted with generic, can use tightly-fitted strip caps in place of seal |
| 1000µL Filter Tips | OT-2 Filter Tips, 1000µL | Opentrons | 1 | (box) Can be substituted with generic |
| 200µL Filter Tips | OT-2 Filter Tips, 200µL | Opentrons | 2 | (boxes) Can be substituted with generic |
| 10 ul Filter tips | TipOne Pipette Tips, 10 uL | TipOne | 2 | (boxes) Can be substituted with generic |
| AmpliTaq Gold PCR Mix | AmpliTaq Gold DNA Polymerase 5 mL | ThermoFisher | 1.2 | (mL) |
| Molecular water | Invitrogen RT-PCR Grade Water | Fisher Scientific | 0.912 | (mL) |
| Forward Primer - 515 F | 16S 515F Fluidigm Primer | IDT | 105 | (ul (10uM)) Primer must be diluted from 100uM stocks to 10uM |
| Reverse Primer - 926 R | 16S 926R Fluidigm Primer | IDT | 105 | (ul (10uM)) Primer must be diluted from 100uM stocks to 10uM |
| TBE Buffer (10x) | TBE Buffer 10X Solution, Molecular Biology Grade, UltraPure | Thermo Scientific | 100 | (uL) |
| Agarose | Agarose LE, Molecular Biology Grade, UltraPure | Thermo Scientific | 4 | (g) |
| SYBR Safe | SYBR Safe DNA Gel Stain | Invitrogen | 20 | (uL) Light sensitive - do not expose to light |
| Gel stain loading dye | DNA Gel Loading Dye (6x) | Thermo Scientific | 480 | (ul per plate) |
| 100bp DNA Ladder | Generuler 100 bp DNA Ladder | Thermo Scientific | 6 | (ul per lane on gel) |
| Parafilm | Parafilm M Lab Film | Generic | 1 | (roll) Can substitute with generic brand |
| **Chemicals** |
| RNase AWAY | RNase AWAY Surface Decontaminant | ThermoFisher Scientific | 1 | (bottle) Used to sterilize lab surfaces and equipment |
| EtOH | Ethanol | Generic Brand | 1 | (wash bottle) Must be molecular grade ethanol |
| DI water | Deionized water | Generic | 900 | (mL) |
| **(OPTIONAL) Clean-Up Protocol** |
| AMPure XP Beads | AMPure XP Bead-Based Reagent | Beckman Coulter | 1 | (kit) |
| 96-well magnetic plate | MagDTR 96-Well Magnetic Separator | Edge Biosystems Inc | 1 | Can be substituted with generic brand |
| **(OPTIONAL) Qubit** |
| Qubit Reagents | Qubit dsDNA Quantification Assay Kit | Invitrogen | 1 | (kit) |
| Clear Qubit Assay tubes | 0.5 mL thin-walled, polypropylene tubes | Invitrogen | 98 | Must be correct tubes to allow for fluorometer to read concentration |

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumable may need to be sterilized, some commercial solution may need to be diluted or shielded from light during the operating procedure.

## STANDARD OPERATING PROCEDURE

### Protocol

#### Preparation

1. Dilute primers from 100 uM to 10 uM if not already at 10 uM.
2. Set up PCR under hood by wiping off all surfaces, pipettes, and racks with RNase AWAY and UV sterilizing for 5-10 mins.
3. Map out order of samples on 96-well PCR plate. Make sure to leave a space for a no template control (NTC) and positive control.

#### PCR

1. Make PCR master mix and add 24 ul to each well of PCR plate - possible use on Opentrons OT2 Pipetting Robot.

- 12.5 ul [AmpliTaq Gold 360 Master Mix](commercial_mm)
- 9.5 ul molecular water 
- 1 ul Fwd primer (10 μM) - [515 F-Y](pcr_primer_name_forward)
- 1 ul Rev primer (10 μM) - [926 R](pcr_primer_name_reverse)

| PCR Primer Name | Direction | Sequence (5’ -> 3’)| Sequence (5’ -> 3’) with Fluidigm Adapters | Fluidigm Adapter |
| ----- | ----- | ----- | ----- | ----- |
| [515 F-Y](pcr_primer_name_forward) | forward | [GTGYCAGCMGCCGCGGTAA](pcr_primer_forward) | ACACTGACGACATGGTTCTACA xxx [GTGYCAGCMGCCGCGGTAA](pcr_primer_forward) | CS1-TS-F |
| [926 R](pcr_primer_name_reverse) | reverse | [CCGYCAATTYMTTTRAGTTT](pcr_primer_reverse) | TACGGTAGCAGAGACTTGGTCT xxx [CCGYCAATTYMTTTRAGTTT](pcr_primer_reverse) | CS2-TS-R |

2. Add [1.0](pcr_dna_vol) ul of sample DNA (or molecular water for NTC) to respective wells for a total reaction volume of [25](amplificationReactionVolume) ul per well. Pipette up and down or vortex to fully distribute DNA into master mix.
3. Seal plate with PCR plate seal or strip caps.
4. Load plate onto thermal cycler and select program to run the following steps:

| PCR step | Temperature | Duration | Repetition |
| ----- | ----- | ----- | ----- |
| Initial Denaturation | 95°C | 180s | 1x |
| Denaturation | 95°C | 45s | 30x |
| Annealing | 50°C | 45s | 30x |
| Extension | 72°C | 90s | 30x |
| Final Extension | 72°C | 10min | 1x |
| Hold | 4°C | ∞ | |

#### Quality Control and PCR Clean-Up

2% Agarose Gel
Following PCR amplification, run products through 2% agarose gel to confirm presence of target bands:
1. Make stock solution of TBE buffer (1x) in a 1-L glass container by adding 100 ml of stock TBE buffer (10x) to 900 ml DI water.
2. For a 5.5in x 5.5in gel tray, mix 200 ml of TBE buffer (1x) and 4 g of agarose in a flask. Use scale to weigh agarose.
3. Microwave mixture for 1 minute, followed by 15-30 second intervals. Watch carefully after 1 minute - mixture can bubble out of flask! The agarose should be fully dissolved so that the solution is mostly clear. Wear a protective glove when handling flask as the mixture will be hot.
4. Allow for gel mixture to cool in flask for 5-10 min. While cooling, set up gel tray (5.5in x 5.5in) in gel box. Make sure the tray is oriented properly and sealed tight for gel pouring. Add two gel combs for 20 wells each lane - total of 40 wells.
5. Once cooled to 50°C, add 20 ul of SYBR safe to the mixture and swirl the flask gently to mix (don't create bubbles!). SYBR safe is light sensitive so after adding to mixture, immediately close the vial and store in the dark.
6. Pour the gel mixture and remove any bubbles using a pipette tip.
7. Allow gel to set for 30-45 min.
8. Cut large strips of parafilm or use 8-strip tubes and label each sample as a position on the parafilm/tubes.
9. Pipette 1 ul of blue loading dye onto each sample position or into each tube.
10. Pipette 5 ul of DNA sample into loading dye and pipette to mix 2-3 times.
11. Once the gel is set, fill the gel box with enough TBE buffer (1x) to fully submerge the gel beneath ~1cm of buffer.
12. Carefully add samples (6 ul each) to gel and write down their positions.
13. Add 6 ul of ladder dye (green) to gel.
14. Run gel at 100 V for 40-50 min then visualize on gel reader machine.

(OPTIONAL) Purify PCR products using AMPure beads protocol
1. Follow along with AMPure XP beads manufacturer protocol (begins on page 5 of manual - <https://www.beckmancoulter.com/wsrportal/techdocs?docname=B37419>).
2. Will need magnetic plate and fresh 70% ethanol.
3. Adjust bead ratio - 0.8x beads to sample volume for 16S.
4. End product will be ~40 ul of cleaned DNA eluted in molecular grade water.

(OPTIONAL) Run Qubit on final PCR Products
1. Follow manufacturer protocol for running Qubit: <https://tools.thermofisher.com/content/sfs/manuals/Qubit_dsDNA_HS_Assay_UG.pdf>.

(OPTIONAL) Run Second 2% Agarose Gel on Purified PCR Products
1. Follow along with previous gel instructions.

#### Sequencing Preparation
1. After performing a gel on the PCR products, pipette 10 uL of each sample into their respective wells of a new 96-well PCR plate.
    - Leave well H12 empty for Michigan State's sequencing negative control
3. Seal plate, label with ID and place in freezer till day of shipping.
4. Fill out Illumina Sample Submission form with sample information and 96-well plate format.
    - Can be found online at: [LIMS Project Submission](https://rtsf.natsci.msu.edu/genomics/lims-project-submission.aspx)
5. Login to [LabLink](https://msu.claritylims.com/lablink/login) and create a project for the sequencing run.
6. Upload project and run information, sample submission form and gel images (annotated) to the project.
7. Prepare plates for shipping by obtaining dry ice (5-10lbs depending on quantity of plates), a styrofoam cooler and fitted cardboard box.
8. Place 1-2 inches of dry ice on bottom of styrofoam cooler followed by sequencing plates then the remainder of dry ice.
9. Place lid on cooler (do not tape shut) and place cooler into cardboard box.
10. Tape the cardboard box shut and attach a shipping label.

#### Sequencing Facility Protocol
Information on sequencing is provided by Michigan State University's Genomics Core Facility:

The Genomics Core performs a secondary PCR using dual-indexed, Illumina compatible primers which target the Fluidigm CS1/CS2 oligomers at the ends of the primary PCR products. Amplicons are batch normalized using the Charm Biotech PCR Normalization and Purification kit and the recovered product is pooled. The pool is QC'd and quantified using a combination of Biotium AccuGreen High Sensitivity dsDNA, Agilent 4200 TapeStation HS DNA1000 and Invitrogen Collibri Library Quantification qPCR assays.

Each pool is loaded onto one (1) Illumina MiSeq v2 Standard flow cell. Sequencing is carried out in a 2x250bp paired end format using a MiSeq v2 500 cycle reagent cartridge. Custom sequencing and index primers complementary to the Fluidigm CS1 and CS2 oligomers are added to appropriate wells of the reagent cartridge. Base calling is done by Illumina Real Time Analysis (RTA) v1.18.54 and output of RTA is demultiplexed and converted to FastQ format with Illumina Bcl2fastq v2.20.0. A summary of the run output is provided by MSU and basic QC information about sequence data is provided by the accompanying FastQC reports. For information regarding interpretation of these reports, please see the FastQC Tutorial and FAQ from [MSU's website](https://rtsf.natsci.msu.edu/genomics/technical-documents/fastqc-tutorial-and-faq.aspx).

Data is downloaded using an account on the Genomics FTP server. See the [Genomics FAQ](https://rtsf.natsci.msu.edu/genomics/data-retrieval.aspx) for general instructions. Sequence data typically remains available on the FTP server for 60 days. It is the responsibility of the researcher to download and store data long term. The RTSF Genomics Core only guarantees retention of sequence data for one year from the date of availability.

### Basic troubleshooting guide

Low Volume Post-PCR

- If using strip-caps, ensure they are tightly fitting on wells. Any gap in the lid will allow for some volume to evaporate during the PCR process on the thermal cycler. If using PCR plate seals, spin down the plate after taking it off the thermal cycler to ensure all condensation is drawn back into the well.

Contamination

- If there are contamination bands appearing on the gel, run another PCR ensuring full sterilization of work spaces and equipment under the hood and use new vials of [AmpliTaq Gold 360 Master Mix](commercial_mm) and molecular water. If diluted primers are contaminated, use freshly-made aliquot of primers. 

Weak Amplification

- If you are seeing weak amplification bands on the gel, ensure the master mix and DNA is being fully mixed. You can also increase the concentration of primers or tweak the PCR process on the thermal cycler (increasing # of cycles of PCR or optimize annealing temperature). The addition of Bovine Serum Albumin (BSA) to master mix is also useful in some cases. 

## REFERENCES

1. Miya, M. et al. (2025). MiFish, a set of universal PCR primers for metabarcoding environmental DNA from fishes: detection of more than 230 subtropical marine species. R Soc Open Sci. 2015 Jul 22;2(7):150088. doi: 10.1098/rsos.150088.

## APPENDIX A: DATASHEETS
Not applicable.
