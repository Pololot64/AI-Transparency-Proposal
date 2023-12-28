# AI Transparency Proposal
Proposal to eliminate modes of model collapse, information source uncertainty, and plagiarism using simple text lookup methods and standard API's. 

## Background: The Problem

Due to the prevalence of unlabeled, AI generated text on the internet, it has been increasingly difficult to discern "good" from "bad" data.

This is a problem for several reasons:
  * Model Collapse - Generative AI being is trained on output from itself. Companies can use internal data to determine if text was previously generated by their model. Other parties do not have this luxury (Possibly GROK).
  * Source Veracity - Teachers and institutions of higher education are forced to resort to faulty solutions that claim to detect AI data. This can cause more harm than good due to misunderstandings about the nature of AI.
  * Transparency - AI companies cannot be held accountable for unlabeled data they create. This is also a lost opportunity for model improvement based on public feedback.

## Proposed Solution: Public Standardized "did you make this" API
  * AI companies already store all generated text.
  * Create a standard API endpoint for companies to implement that allows a "yes"/"no" response to a "did you make this" request by performing a quick lookup.
  * Everyone can access these free to use and open API's

![flowchart1](https://github.com/Pololot64/AI-Transparency-Proposal/assets/31389383/b1ea0467-acb7-4381-9555-f54d939d93c7)

## Benefits
  * Free to use, public, open API's
  * Standardization allows for:
    * Quick and easy lookup for multiple AI providers at once.
    * Easy integration into social media (X, Facebook) or teaching platforms (Canvas, TurnItIn, Schoology).
    * Easy implementation (if AI companies can train giant models, they can provide an API like this).
  * Privacy:
    * No data other than "yes"/"no" is returned and requests are "anonymous".
  * A long term solution to data source veracity and transparency on the internet.

## Potential Problems
  * Short commonly used text samples may generate false positives.
    * Possible solution is to only check larger bodies of text for plagiarism.
    * Data can be cross referenced with other public domain material e.g. the Bible which is often marked as plagiarism by current "AI Detection" systems.


Last Updated: 12/28/2023




The term "AI" is used loosely in this document to refer to text based generative AI models e.g. Chat GPT, Copilot, Grok.
