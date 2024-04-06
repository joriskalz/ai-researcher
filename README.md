# Fork of [Binxly/ai-researcher](https://github.com/Binxly/ai-researcher) which is a Fork of [AI-Researcher](https://github.com/mshumer/ai-researcher) by [@mattshumer](https://github.com/mshumer)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/joriskalz/ai-researcher/blob/main/Claude_Researcher_Google_API.ipynb)

This project is an evolving fork of the `Binxly/ai-researcher` repository, which itself is a fork of the original `ai-researcher` repository created by [@mattshumer](https://github.com/mshumer). The original version utilized Claude 3 and SERPAPI to conduct research, while the `Binxly/ai-researcher` fork modified the project to use Google Search API for searching capabilities. This fork builds upon those changes with further enhancements. Below are the details of the modifications:

## Changes Made

1. **Switched to OpenAI**:
   The underlying AI model has been switched from Claude 3 to OpenAI's GPT-3 model for improved performance and flexibility.

2. **Parsing Improvements**:
   The web search function has been enhanced to parse the content from the original website, rather than relying solely on the Google meta data. This change allows for more comprehensive and accurate information retrieval.

## ToDo

- [x] Switch to OpenAI
- [x] Improved parsing of the google search result
- [ ] Parse the content from the original website, not just from the Google meta data
- [ ] Add Azure OpenAI support

## Acknowledgements

Credit goes to the original creator, [@mattshumer](https://github.com/mshumer), for the foundational work on the `ai-researcher`, and to [Binxly](https://github.com/Binxly) for their enhancements in the `Binxly/ai-researcher` fork. The changes made in this fork aim to further improve upon their work.

## Notice of Modifications

This document outlines the changes from the `Binxly/ai-researcher` fork, which itself modified the original project. It should be noted that while the core functionality remains the same, additional optimizations and features have been introduced to enhance the AI Researcher tool.

---
This document is for the forked project and should be used in conjunction with the documentation from the `Binxly/ai-researcher` fork and the original project for a complete understanding of the system's capabilities and usage.