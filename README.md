# File Integrity Verification Using SHA-256

## Project Overview
This project demonstrates file integrity verification using the SHA-256 cryptographic hashing algorithm.

## Objective
To detect unauthorized or accidental modifications to files by comparing their current SHA-256 hashes against previously generated baseline hashes.

## Files Included
- employee_records.txt
- security_policy.txt
- system_config.txt
- baseline_hashes.csv
- integrity_results.csv

## Methodology
1. Create sample text files.
2. Generate SHA-256 hashes for each file.
3. Store the original hashes in baseline_hashes.csv.
4. Modify employee_records.txt to simulate an integrity change.
5. Recalculate the SHA-256 hashes.
6. Compare current hashes with baseline hashes.
7. Record the verification results in integrity_results.csv.

## Expected Results
- employee_records.txt - MODIFIED
- security_policy.txt - UNCHANGED
- system_config.txt - UNCHANGED

## Technology Used
- Windows PowerShell
- Git and GitHub
- SHA-256 Hash Algorithm

## Conclusion
The project demonstrates how cryptographic hashing can be used to identify file modifications and support basic file integrity monitoring.
