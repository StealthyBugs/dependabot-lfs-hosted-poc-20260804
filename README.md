# GitHub Desktop inert PR-protocol test

This branch is an isolated, harmless proof for GitHub Desktop's PR-protocol
checkout path and the Git LFS tracked `.lfsconfig` custom-transfer boundary.
The adapter talks only to a loopback test server, writes one constant local
marker, hydrates the fixed bytes `PR2_UNIQUE_20260804\n`, and transmits no
host data.
