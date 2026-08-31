---
layout: default
title: Research
description: "Research by Lateef Adeleke on low-resource speech technology, documentary linguistics, corpus-accountable grammar, variation, and linguistically informed AI evaluation."
permalink: /research/
---
<section class="page-hero"><div class="shell"><p class="kicker">Research</p><h1>Language structure, primary data, and low-resource AI</h1><p class="lead">My research asks how carefully documented linguistic data can improve both our understanding of language and the technologies built for languages that remain underrepresented in modern AI.</p></div></section>
<div class="content">
## 1. Low-Resource Speech Technology

**How can speech systems learn robustly from small, heterogeneous, linguistically complex datasets?**

I build and evaluate automatic speech recognition systems for languages with limited transcribed speech resources. My current work investigates cross-lingual transfer, data-efficient adaptation, speech-style mismatch, naturalistic versus constrained data, tonal contrasts, and the limits of multilingual pretraining.

A central concern is ecological validity: models that perform well on carefully elicited or read speech may behave very differently on spontaneous documentary recordings. I therefore treat recording style, speaker and community variation, and linguistic structure as central experimental variables rather than noise to be removed.

**Methods and tools:** Python, PyTorch, Hugging Face, Whisper, XLS-R / wav2vec-style models, WER/CER, controlled data splits, error analysis, and reproducible training pipelines.

## 2. Linguistically Informed AI Evaluation

**What do aggregate metrics hide about what speech and language models actually learn?**

Word Error Rate and Character Error Rate are useful, but they can collapse linguistically different error types into a single score. My work develops and applies evaluation approaches that ask which phonological, tonal, morphological, and grammatical distinctions are preserved or lost by a model.

This direction is represented by my AfricaNLP 2026 work on multilingual ASR for Yorùbá and Uneme, where phonological-feature and tone-sensitive evaluation reveals systematic model behavior that word-level accuracy alone cannot show.

[Read the AfricaNLP 2026 paper →](https://aclanthology.org/2026.africanlp-main.14/)

## 3. Corpus-Accountable Grammar & Variation

**How can grammatical description capture the variation that actually occurs in documentary corpora?**

I study tense, aspect, negation, grammatical tone, focus, movement, and clause structure in underdescribed African languages, especially Edoid languages. I am particularly interested in the relationship between targeted elicitation and naturalistic evidence, and in grammatical descriptions that remain accountable to patterns across speakers, communities, and discourse contexts.

My work treats variation not as a defect in the dataset but as an empirical fact with consequences for linguistic theory, documentation practice, and computational modeling.

## 4. Documentation-to-Technology Pipelines

**How can documentary resources become computationally useful without stripping away linguistic richness?**

For many underdescribed languages, computational work cannot begin with a large downloaded benchmark. It begins with field relationships, recording decisions, transcription conventions, annotation, lexical analysis, and language-specific knowledge.

I therefore work across the full pipeline: audiovisual documentation → transcription and annotation → corpus and lexicon development → grammatical analysis → speech datasets → model training and evaluation. This creates a feedback loop in which documentation informs technology and model errors generate new linguistic questions.

<div class="callout"><strong>Research principle:</strong> Language documentation should not end with an archive, and language technology should not begin with a downloaded dataset.</div>

## Empirical focus

Much of my current work centers on **Uneme**, an Edoid language of Nigeria, alongside comparative and grammatical research on related Edoid languages and computational evaluation involving Yorùbá. Uneme is a major empirical laboratory for my broader questions about documentation, variation, speech technology, and linguistically informed AI—not the limit of those questions.
</div>
