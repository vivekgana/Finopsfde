# Fed Rate Video Analyzer

## Objective

Find, transcribe, and summarize publicly available Federal Reserve video briefings for research workflows. The tool should distinguish what a speaker explicitly said from derived interpretation and must not represent a summary as an official policy announcement.

## Discovery questions

- Which official channels, video types, languages, and publication windows are in scope?
- Is the goal search, transcription, topic classification, or tracking explicit rate statements?
- What are the required source links, timestamp precision, and correction process?
- Who reviews summaries before they are distributed or used in decisions?

## Inputs and outputs

- **Inputs:** Public video URLs or approved files, publication metadata, and a defined vocabulary of rate-related topics.
- **Outputs:** Timestamped transcript excerpts, source-linked summaries, topic tags, and uncertainty or transcription flags.
- **Integrations:** Approved video retrieval, speech-to-text, document search, and analyst review tools.

## Candidate workflow

1. Retrieve only authorized public content and preserve its source URL, publication date, and version.
2. Transcribe speech and align excerpts to video timestamps; flag low-confidence passages.
3. Identify relevant passages without inferring a policy decision beyond the source language.
4. Produce concise summaries with direct citations to timestamped excerpts.
5. Route ambiguous or consequential statements to an analyst and retain corrections.

## Measures and validation

- Track retrieval success, transcription error, timestamp alignment, citation coverage, and reviewer correction rate.
- Evaluate against a human-reviewed sample that includes accents, overlapping speech, technical terms, and poor audio.
- Verify summaries against the original video and test updated, removed, or inaccessible source content.

## Controls and FDE deliverables

Respect source terms and copyright; do not redistribute full transcripts or media without permission. Preserve provenance, label generated summaries, avoid presenting analysis as investment advice, and require review for material claims.

Document source policy, transcript evaluation, citation format, review workflow, error handling, and known limitations.
