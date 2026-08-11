# Validate input before writing to storage

Config parsing was duplicated in three call sites. Now there is one loader with defaults in a single place.

Change #1 of 3 on branch `pr/20260811-115807-1-validate-input-before-writing-to-storage`.
