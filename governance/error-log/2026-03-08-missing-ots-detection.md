# Missing OTS Detection Record

Date: 2026-03-08  
Repository: MaMeeFarm-Primary-Dataset

## Context

During repository maintenance, three data unit JSON files
were detected without corresponding OpenTimestamps proof files.

Affected Data Units:

- DU-00561
- DU-01562
- DU-01729

## Action Taken

OpenTimestamps proofs were generated and committed
to the repository.

The proof file for DU-01729 was relocated to the
`ots/` directory to maintain repository structure consistency.

Files without OTS verification were temporarily recorded
under audit tracking.

## Integrity Note

No existing dataset records were modified.

This entry documents the operational correction
for transparency and traceability.

DGCP | MMFARM-POL-2025
