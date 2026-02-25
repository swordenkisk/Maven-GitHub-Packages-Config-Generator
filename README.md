Maven × GitHub Packages Config Generator
The pain I spotted in the docs: every developer must manually copy-paste and edit XML snippets for settings.xml, pom.xml, and CI/CD workflows — replacing OWNER, USERNAME, TOKEN, REPOSITORY by hand, across multiple files, with subtle rules (lowercase owner, specific artifact naming, SNAPSHOT flags). One typo = a cryptic 422 error.
What it does
A single-page interactive config generator with an industrial blueprint aesthetic — you fill in the form, it outputs perfect XML and YAML instantly:
Section
What it generates
Credentials
~/.m2/settings.xml with auth tokens
Repository
Multi-repo support with dynamic server IDs
Package
pom.xml distribution + dependency blocks
CI/CD
Full GitHub Actions publish.yml workflow
Key features:
🔴 Live validation — warns on uppercase owners, bad artifact IDs, wrong token format
⚡ Syntax highlighted output — XML/YAML with color coding, placeholders highlighted in amber
📋 Copy + Download per file, or export all at once
➕ Multi-repository — add as many repos as needed
✅ Step tracker — shows your completion progress
☑️ Toggle outputs — only generate what you need
⚡ Maven cheatsheet built in
