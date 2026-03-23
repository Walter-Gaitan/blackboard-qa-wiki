# Blackboard QA Wiki

Documentation site for Blackboard LMS Quality Assurance processes, built with [MkDocs](https://www.mkdocs.org/) and the [Material theme](https://squidfunk.github.io/mkdocs-material/).

## 📖 View the Wiki

**Live site**: Visit the deployed GitHub Pages site (link available in the repo's About section).

## 🛠️ Local Development

### Prerequisites
- Python 3.x

### Setup

```bash
# Install dependencies
pip install mkdocs mkdocs-material

# Start local dev server (auto-reloads on changes)
mkdocs serve

# Build the static site
mkdocs build
```

The local dev server runs at `http://127.0.0.1:8000/`.

## 📁 Structure

```
docs/
├── index.md                  # Homepage
├── QA_Onboarding_Guide.md    # New hire onboarding
├── tqa_checklist.md           # TQA 48-step checklist
├── tqa_advice.md              # TQA advice & tips
├── tqa_form_mapping.md        # TQA form field reference
├── student_qa_checklist.md    # SQA 43-step checklist
├── sqa_advice.md              # SQA advice & tips
├── form_mapping.md            # SQA form field reference
├── psqa_checklist.md          # PSQA 10-step checklist
├── psqa_form_mapping.md       # PSQA form field reference
├── qa_protocols.md            # Standards & guidelines
├── edge_cases.md              # 35 common edge cases
├── program_quirks.md          # Program-specific exceptions
├── automation_setup.md        # Playwright test setup
└── test_reference.md          # Test file reference
mkdocs.yml                     # MkDocs configuration
```

## 🚀 Deployment

The wiki deploys automatically to GitHub Pages via GitHub Actions on every push to `main`/`master` that changes files in `docs/` or `mkdocs.yml`.

**First-time setup**: Go to **Settings → Pages → Source** and select **GitHub Actions**.
