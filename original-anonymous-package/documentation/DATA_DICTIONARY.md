# Data Dictionary

## Files

- `data/llm_static_analysis_review_data_anonymized.xlsx`: anonymized workbook with protocol, filters, and screening sheets.
- `data/csv/protocol.csv`: research questions, search string, inclusion/exclusion criteria, and search execution notes.
- `data/csv/filters.csv`: allowed screening statuses and criterion definitions.
- `data/csv/screening_scopus.csv`: Scopus candidate-study screening records.
- `data/csv/screening_ieee.csv`: IEEE Xplore candidate-study screening records.
- `data/csv/screening_wos.csv`: Web of Science candidate-study screening records.

## Screening Columns

- `ID`: candidate-study identifier used during screening.
- `Title`: study title.
- `Authors/Year`: bibliographic authors and publication year of the screened study. These are literature metadata, not package-author identities.
- `Venue/Source`: publication venue or indexing source.
- `Study Type`: type assigned during screening.
- `Related RQs`: research questions addressed by the study.
- `Link/DOI`: DOI or source link.
- `Screening Status`: inclusion or exclusion decision.
- `Screening Rationale`: English rationale derived from the screening criteria.
- `Supporting Excerpt`: source excerpt retained only when already in English and free of package-author identifiers.
