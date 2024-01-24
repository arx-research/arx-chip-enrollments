# Arx ERS Chip Enrollments

This repo contains the Arx ERS chip enrollments, organized by chain. You can use this to reference a given enrollment that a chip has been added to, as we as the IPFS CID of the merkle proof data.

## Notes

### Deprecated Networks

The ERS deployment on Goerli is deprecated and the files stored in this repo are organized in a legacy fashion as such. They are not directly compatible with the latest versions of `ers-scripts`.

### Chip Enrollment Files

Due to the number of enrollment files created (one per chip in enrolled by a manufacturer in ERS), files are compressed into `manufacturerEnrollments.tar.gz` prior to being committed (previously `arxChips.tar.gz` for Goerli).