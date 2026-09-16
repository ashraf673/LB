# Let's Backup Android v0.4

Backup-selection prototype.

Added:
- Album/folder list from MediaStore relative paths
- Select all / individual albums
- Date-range picker
- Exact selected source-byte size calculation
- SAF destination directory selection
- Persistent SAF permission attempt
- Existing scanner and SHA-256 foundations

This version still does not write the final `.lb.zip`. The next engine step is
ZIP64 streaming, manifest/checksum generation, free-space validation and
post-write archive verification.
