# Open Source Repository Scan Reports 

[![Archive Report 🗑](https://github.com/spencerlepine/open-source-crawler-output/actions/workflows/archive-report.yml/badge.svg?branch=main)](https://github.com/spencerlepine/open-source-crawler-output/actions/workflows/archive-report.yml) [![Restore Report ♻️](https://github.com/spencerlepine/open-source-crawler-output/actions/workflows/restore-report.yml/badge.svg?branch=main)](https://github.com/spencerlepine/open-source-crawler-output/actions/workflows/restore-report.yml)

> An archive of the [web crawler + code scanner](https://github.com/spencerlepine/open-source-crawler) for open source repos found across GitHub.

## 🌟 Features
- Create folder for every repository analyzed, under `<rootDir>/username/reponame` convention
- Stores `.sarif` CodeQL results (static code scans for security vulnerabilites)
  - CodeQL: [learn more](https://codeql.github.com/)
  - SARIF: [learn more](https://docs.github.com/en/code-security/code-scanning/integrating-with-code-scanning/sarif-support-for-code-scanning)
- Stores `typos.diff` with any/all typos found during scan
  - Typo Detection: [`typo-cli`](https://github.com/crate-ci/typos) spell checker

## 🤖 Actions
- [Archive](https://github.com/spencerlepine/open-source-crawler-output/actions/workflows/archive-report.yml) action to move project folders to trash
- [Restore](https://github.com/spencerlepine/open-source-crawler-output/actions/workflows/restore-report.yml) action to move project folders to root dir
