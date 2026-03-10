# Intro

Never used Uyuni? Learn about the basic concepts, basic deployment and first steps!

# Artifacts

You can easily download artifacts built from the latest commit on the `main` branch.

Go to the [GitHub workflow](../../actions/workflows/build_and_archive.yml?query=branch%3Amain), click on the most recent build, and you will find the artifacts for the PDF and the EPUB.

# Build tests

The following branches are under active development and continuously tested:

| Branch | Status |
| ------ | ------ |
| `main` | ![Build status](../../actions/workflows/build_and_archive.yml/badge.svg?branch=main) |

# Build it on your own

## Requirements

- Podman

## PDF

```bash
./create-book-pdf.sh
```
You will find the resulting PDF at the `build/` folder.

## EPUB

```bash
./create-book-epub.sh
```
You will find the resulting EPUB at the `build/` folder.

