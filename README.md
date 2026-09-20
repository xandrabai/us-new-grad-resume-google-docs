# U.S. New-Grad Resume Tailoring

A Codex skill that saves U.S. new graduates the unnecessary time spent manually formatting resumes. It produces an evidence-based, one-page resume tailored to a specific job description, then automatically (after you allow it) uploads the approved version to Google Docs for backup or final human revision.

## What it does

- Analyzes the target role, required skills, keywords, and evidence gaps.
- Independently evaluates the resume from the resume and job description, using established U.S. resume practices; no external reviewer output is required.
- Writes bullets that connect action, business or user purpose, and impact.
- Optimizes content and layout for a readable, balanced one-page resume rather than leaving excess whitespace or shrinking the type excessively.
- Bolds meaningful, supported quantitative impact so the strongest outcomes are easy to scan.
- Uses candidate-supplied degree details and asks when a full official degree name is missing or ambiguous.
- Shows a local rendered preview for feedback, then automatically uploads the approved version to Google Docs for backup or final human revision.

## Install

Copy the `us-new-grad-resume-google-docs` directory into your Codex skills directory, then invoke it with:

```text
$us-new-grad-resume-google-docs
```

Provide a current resume and the target job description. You may optionally paste feedback from an external resume reviewer after the skill's independent evaluation; it checks that feedback against the job description and your supplied evidence rather than accepting it uncritically.

## License

MIT. See [LICENSE](LICENSE).
