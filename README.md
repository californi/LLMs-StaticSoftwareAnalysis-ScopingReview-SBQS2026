# Large Language Models for Static Software Analysis: A Scoping Review

Replication package for submission #32684, SBQS 2026, Technical Papers Track.

## Authors and affiliations

1. Yasmin das Neves Silva — Institute of Science, Technology and Innovation (ICTIN), Federal University of Lavras (UFLA), São Sebastião do Paraíso, Minas Gerais, Brazil.
2. Gustavo Vitor da Silva — Institute of Science, Technology and Innovation (ICTIN), Federal University of Lavras (UFLA), São Sebastião do Paraíso, Minas Gerais, Brazil.
3. Marcio Ribeiro — Institute of Computing, Federal University of Alagoas (UFAL), Maceió, Alagoas, Brazil.
4. Bento Rafael Siqueira — Department of Applied Computing (DAC), Federal University of Lavras (UFLA), Lavras, Minas Gerais, Brazil.
5. Samira Santos da Silva — Institute of Science, Technology and Innovation (ICTIN), Federal University of Lavras (UFLA), São Sebastião do Paraíso, Minas Gerais, Brazil.

## Contents and use

- `data/included_studies_58.csv`: index of the same 58 publications listed in the submitted manuscript, with bibliographic metadata from the supplied BibTeX, with A26 publication year updated to 2026 from the publisher’s final record and B14 author order corrected to Klieber, Flynn from the published PDF. IEEE IDs are B01–B14, as used in the manuscript.
- `data/excluded_nonduplicates_13.csv`: the same 13 non-duplicate exclusions in the manuscript.
- `data/candidate_reconciliation_83.csv`: an explicit comparison of all 83 original candidate records with the manuscript tables. Original IEEE IDs A01–A18 are mapped to manuscript IDs B01–B18.
- `original-anonymous-package/`: preservation copy of the publicly available review package. Its workbook, CSVs, original names, statuses, and checksums have been retained. Anonymous identity labels inside these historical files describe the earlier version; the authors of this package are identified above.
- `documentation/RECONCILIATION.md`: discrepancies, mappings, and limits of reconstruction.
- `documentation/PROVENANCE.md`: source and preparation record.
- `manifest_sha256.csv`: checksums for this identified release.

The protocol is in the original package. Use the 58-publication index to identify the corpus reported by the article, and use the reconciliation file when comparing it with candidate-sheet statuses. These files expose inconsistencies rather than silently changing screening records. They do not represent a new search or re-execution of the review.

## AI support

The two first authors manually screened studies by reading titles and abstracts; no LLM was used for study screening or inclusion and exclusion decisions. Google Gemini, accessed through an institutional account, assisted only in preparing the final table of articles after study selection. The authors checked and confirmed its output. The available package does not include model versions, prompts, or interaction logs for this table-preparation assistance. AI also supported editorial and consistency work during camera-ready preparation.

## Scope

Search window: June 12–24, 2026. Databases: IEEE Xplore, Web of Science, and Scopus. The original query and reported flow are preserved. The package has 83 candidate records, not complete raw exports of all 1,683 retrieved records. No search update, snowballing, new screening, experiment, or meta-analysis was performed during camera-ready preparation.

## License

The package retains the original CC BY 4.0 license. See `LICENSE.txt` and the original preserved license file.
