# MaMeeFarm™ Primary Dataset

This repository contains **primary real-world data** collected directly
from daily life and field activities at MaMeeFarm™, Thailand.

## What this dataset is
- Raw images and files captured from real events
- No narrative, no NFT metadata, no derivative content
- Data governed under the DGCP (Data Governance & Continuous Proof) framework

## What this dataset is NOT
- Not a proof repository
- Not an NFT collection
- Not edited or curated storytelling data

## Data Integrity
Each data batch may include:
- SHA-256 hashes
- OpenTimestamp (.ots) files
- IPFS CIDs (where applicable)

## Governance & License
DGCP | MMFARM-POL-2025  
All data remains attributable to MaMeeFarm™ and must preserve provenance
and license reference upon reuse.

# MaMeeFarm™ Primary Dataset

This repository contains **primary real-world data** collected directly
from daily life and field activities at MaMeeFarm™, Thailand.

## What this dataset is
- Raw images and files captured from real events
- No narrative, no NFT metadata, no derivative content
- Data governed under the DGCP (Data Governance & Continuous Proof) framework

## What this dataset is NOT
- Not a proof repository
- Not an NFT collection
- Not edited or curated storytelling data

## Data Integrity
Each data batch may include:
- SHA-256 hashes
- OpenTimestamp (.ots) files
- IPFS CIDs (where applicable)

Timestamp order reflects system anchoring time,
not a reconstructed event narrative.

## Operational Constraints
Data capture and data commit may not occur on the same calendar day.

MaMeeFarm™ operates under real-world constraints, including:
- Limited and intermittent electricity supply
- Manual labor–based workflows
- Field-first data capture, system-later synchronization
- No always-on infrastructure or continuous power availability

As a result:
- Some data may be committed after the actual event date
- Cryptographic hashes and OpenTimestamp records reflect
  system availability, not narrative intent or data alteration

This delay is a documented operational condition,
and must not be interpreted as data manipulation or post-event fabrication.

## Data Structure Overview
- `dataset/data-unit/<id>/`
  - `dataunit_<id>.json` — primary structured data
  - `dataunit_<id>.md` — human-readable description
  - `hash/dataunit_<id>.sha256` — SHA-256 sidecar hash for integrity verification

- `DGCP_dataunit_<id>.json.ots`
  - OpenTimestamp receipt anchoring the hash of the corresponding data unit
  - Stored at repository root for linear audit and simplified verification

## Governance & License
DGCP | MMFARM-POL-2025  

This dataset is part of the MaMeeFarm™ real-world data archive.
All data remains attributable to MaMeeFarm™ and must preserve
provenance, integrity references, and license terms upon reuse.

