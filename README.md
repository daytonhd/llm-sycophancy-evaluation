# LLM Sycophancy Evaluation

Collaborative CS 410/510 Trustworthy AI final project at Portland State University.

**Team:** Dayton Davis, Isaiah Dawkins, Shanice Uwase

## Project Summary

We evaluated whether system prompts could reduce LLM sycophancy using a Syco-Bench-based experiment.

LLM sycophancy happens when a model validates or agrees with a user's claim even when correction would be more accurate. This is a reliability and safety issue because fluent, supportive responses can still reinforce false or unsafe beliefs.

## Experimental Design

The experiment tested six system-prompt conditions across three target models and four Syco-Bench sub-tests.

**Target models:**
- Claude Haiku 4.5
- Grok 3 Mini
- Qwen 2.5 72B

**Prompt conditions:**
- No system prompt baseline
- Agreeable sycophancy-inducing control
- Direct anti-sycophancy prompt
- Principle-based honesty prompt
- Independent reviewer role prompt
- Reasoning-before-answering prompt

**Syco-Bench sub-tests:**
- Pickside
- Mirror
- Whosaid
- Delusion

The full experiment covered 72 model-prompt-test cells and produced approximately 14,000 LLM judge scores.

## Main Findings

- System prompts changed measured sycophancy, especially on Pickside and Mirror.
- Prompt effects were model-specific and inconsistent.
- No prompt worked reliably across all models and all sub-tests.
- Delusion acceptance did not show statistically reliable improvement.
- Some anti-sycophancy prompts risked pushing models toward contrarian behavior instead of calibrated accuracy.

## My Role

I contributed to the project framing, analysis, technical report, and final presentation.

## Original Project Page

The original collaborative project page was maintained through a teammate's GitHub:

https://isaiahdawkins12.github.io/syco-bench-prompts/

## Portfolio Note

This repository is a portfolio summary of my contribution to the collaborative project. It is not the original team repository.
