# CV refresh audit — 26 October 2026

This checklist distinguishes verified source edits from claims still needing evidence before merging.

## Updated in CV.tex
- Current affiliation and header: Department of Geography, University of Georgia, Athens, GA.
- Education: Ph.D. in Geography (in progress), Aug 2026–Present; Weiming Hu.
- New UGA Graduate Research Assistant role starting Aug 2026 (general research context and verified HPC work).
- Research interests generalized to GIScience, GeoAI, remote sensing, environmental and climate applications; no dissertation topic asserted.
- Peer-reviewed journal articles separated from the arXiv preprint (arXiv:2511.07231).
- Removed unsubstantiated claim that UGA assistantship is renewable throughout the Ph.D.
- Ordered Education before Research Interests; Research Experience before Conference Presentations.
- Simplified and updated institutional header while retaining established email, ORCID, Scholar, website, GitHub links.

## Check before final merge
- **MPI-SP tenure (resolved)**: Contract end confirmed by the author as 31 Jul 2026. Retained that date irrespective of physical departure.
- **UB Clean Air consultancy**: CV says Sep 2024–Present. Confirm still ongoing, or insert end month.
- **WASH manuscript journal status**: arXiv update verified March 2026; preprint label is conservative. Confirm formal journal acceptance/publication/review status before changing label.
- **Author name spelling**: Published articles use Suh, Y.; confirm whether document display name should be “Yong-Hun Suh” vs “Yonghun Suh.”
- **M.A. vs M.S.**: Original CV and project education reference say M.A. in Geography, while an earlier conversational summary refers to M.S. Preserve original **M.A.** pending official diploma/transcript check.
- **Teaching and awards**: Historical entries carried forward as is; confirm attribution, award titles, and dates against supporting documents.
- **2027 AAG abstract**: Do not claim an accepted presentation solely because an abstract was submitted.
- **UGA assistantship**: Treat as employment under Research Experience, not a competitive award absent supporting documentation.
- **Research specifics**: The GraphCast workflow has concrete evidence; omit claims that future experiments, papers, or methods are complete.
- **Current conference publication claims**: Check oral vs poster vs coauthor-only presentation status before updating descriptions.
- **PDF**: The pull-request validation workflow has compiled the edited LaTeX successfully (GitHub Actions run 40433637664, 27 Oct 2026). The resulting four-page PDF was rendered and inspected: the MPI-SP entry begins on page 2; the ROKA entry remains together on page 3; Honors & Awards begins on page 4. The PDF committed on main has **not** been updated.

## Author feedback incorporated (26 October 2026)
- Added official UGA Geography mailing address at 210 Field St., Room 204, Athens, GA 30602. This is the **department** address; it is not claimed to be an individual mailbox.
- Retained clickable, visibly underlined links and supplied identifiable link text or printable identifiers for email, ORCID, Google Scholar, academic website, and GitHub.
- Used `Ph.D. Student in Geography` in Education with Aug 2026–Present rather than implying candidacy or supplying an unconfirmed completion year.
- Linked to the verified `YONGHUNI/s2s-ar-forecasting` repository from the GraphCast/HPC research bullet.
- Retained MPI-SP contractual 31 Jul 2026 end date as confirmed by the author.
- Used `Preprint` plus linked arXiv ID, avoiding the redundant phrase `arXiv preprint` under the Preprints heading.
- Removed the `In English` presentations subheading; retained `In Korean` for non-English conference presentations.
- Added the verified DOI 10.16879/jkca.2024.24.2.089 for the landslide article; kept visible DOI for the Social Science & Medicine article. The 2023 population paper's DOI was subsequently verified as 10.16879/jkca.2023.23.1.021. Per the author's preference, each visible DOI string links directly to its publisher-hosted article page (with free PDF access), rather than to doi.org. The redundant `Free full text` links have been removed. The displayed DOI strings remain accurate bibliographic identifiers.
- Retained Republic of Korea Army military experience in `Work Experience`, not `Service`, because the latter denotes academic/professional service in US CVs.
- Added Nix (flakes) to Reproducibility & Publishing.

## Additional review of uploaded CV.pdf (26 October 2026)
- Original four-page PDF showed an overly stretched 2023 article citation and a print-unfriendly full publisher URL. Applied ragged-right body alignment and shortened the visible publisher link without changing the official citation.
- Journal of the Korean Cartographic Association editorial assistantship moved from Work Experience to Academic Service. Student Council Treasurer appears first based on later end date.
- Removed generic introductory statements that duplicated the substantive research bullets in MPI-SP, SNU research projects, and Korea Environment Institute.
- Replaced the broad UGA RA research-scope bullet with a project-specific subseasonal atmospheric-river forecasting description based on the public research repository.
- Used `needspace` to prevent orphaned institutional headings and split awards. Updated the Nix LaTeX environment for consistent local/CI builds.
- Four-page PDF compiled successfully and visually inspected. Maintained the previously updated header unchanged in this review.

## Later layout iteration
Consider a more conventional academic-CV typographic design: 10.5–11 pt readable font, consistent date alignment, moderate whitespace, section headings that do not require a 1.2-inch left gutter, no photo, linked DOI/preprints, running page numbers, and a short header. Preserve complete academic activity; do not force a one-page résumé.
