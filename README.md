# pg_variables — Windows x64

[日本語](README_ja.md) | English

pgextwin provides **unofficial Windows x64 binaries** for [pg_variables](https://github.com/postgrespro/pg_variables). pg_variables provides session variables for PostgreSQL.

## Download and compatibility

Use the [latest published Release](https://github.com/pgextwin/pg_variables/releases/latest) or [all Releases](https://github.com/pgextwin/pg_variables/releases). Packages for PostgreSQL **14–18** are listed in the [pgextwin catalog](https://pgextwin.github.io/website/en/). Use only the ZIP matching your PostgreSQL major. PostgreSQL 14 community support ends November 12, 2026; older downloads may remain available.

## Installation

1. Back up the relevant PostgreSQL installation and check the [upstream documentation](https://github.com/postgrespro/pg_variables).
2. Stop PostgreSQL before replacing installed files, then extract the ZIP for the matching major.
3. Copy the files under lib/ and share/extension/ (if included) into the corresponding directories of your PostgreSQL installation.
4. Start PostgreSQL and run CREATE EXTENSION pg_variables; in the database that needs it.

Verify the ZIP using the Release's SHA256SUMS.txt. Check the Release page for any attached SPDX SBOM, vulnerability report, and signed attestations. Test before production use.

## License and help

Refer to [upstream pg_variables](https://github.com/postgrespro/pg_variables) for functionality and limitations. This is an independent community-built package, not an upstream-endorsed Windows distribution. Check the package's license notices.
