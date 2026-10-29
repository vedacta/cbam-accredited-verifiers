# CBAM accredited verifiers

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23778090.svg)](https://doi.org/10.5281/zenodo.23778090)

Which firms are accredited to verify emissions under the EU Carbon Border Adjustment Mechanism (CBAM), and which national accreditation bodies accredit CBAM verifiers, including those that accept verification firms from outside the EU.

On the checked date the European Commission had not yet published its own list of accredited CBAM verifiers ([CBAM verification page](https://taxation-customs.ec.europa.eu/carbon-border-adjustment-mechanism/cbam-verification_en)). This list is read from each accreditation body's own decision.

Files:

- [`verifiers.json`](verifiers.json) / [`verifiers.csv`](verifiers.csv): accredited CBAM verifiers (checked 18 October 2026) with country, accreditation body, date of the accreditation decision, CBAM activity groups and a link to the decision. Activity groups are those of Annex I to Delegated Regulation (EU) 2025/2551.
- [`accreditation-bodies.json`](accreditation-bodies.json) / [`accreditation-bodies.csv`](accreditation-bodies.csv): the 29 EU and EEA national accreditation bodies from the Commission's "State-of-play CBAM accreditation" (21 October 2026): agreed to provide CBAM accreditation, ready to accept applications, agreed to accredit third-country applicants, already accepting third-country applications. In the JSON, `null` means N/A in the Commission's table.

Explained, with what an exporter outside the EU should ask a verifier: **[CBAM verifiers guide on the CBAM Exporter Pack](https://cbam.vedacta.com/guides/cbam-verifiers)**. Plan the verification visit and documents with the free [CBAM verification planner](https://cbam.vedacta.com/cbam-verification-planner).

## Sources

- Verifiers: the accreditation decisions linked in each row (ESYD, Accredia, Swedac). Accredia's news item of 6 October 2026 gives other activity groups for RINA and SGS than its signed decision Rev. 01; the decision is used.
- Accreditation bodies: European Commission, [State-of-play CBAM accreditation](https://taxation-customs.ec.europa.eu/carbon-border-adjustment-mechanism/cbam-verification_en) (PDF, 21 October 2026).

More firms may have been accredited since the checked date. The accreditation body's register is what counts; once the Commission publishes its list, that list is the reference.

## Licence

Data and text: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Credit "Vedacta, cbam.vedacta.com".

Maintained by [Vedacta](https://vedacta.com/). Found an error or a new accreditation? Open an issue.
