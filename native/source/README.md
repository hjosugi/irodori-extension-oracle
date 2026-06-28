# Native Source

The initial source snapshot was copied from `db/oracle.rs` in the desktop app.

Source SHA-256: `fa986acea3255b1bafb25edbe7f0d065c96fe211fc2ee20d5da8e4e832cbea98`.


This directory is a migration staging area for `irodori.oracle`. The active native
ABI shim lives in `src/lib.rs`; engine-specific connect/query/metadata behavior
should move here as the connector runtime contract is wired into the desktop app.

Engine status from `knowledge/engines.json`: `verified`.
