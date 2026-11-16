# A Data Module for the AI Engineering Track

Decision of 16 November 2026. The live [AI Engineering](https://datatalks.club/academy/ai-engineering/) page still shows the earlier draft syllabus. This is the copy that will go on the page.

A LinkedIn comment asked for a data-side module on ingestion, freshness and evaluation datasets, because that is where a lot of production systems break first. I added a named module in the Quality and production block and merged two existing quality modules so the program stays at 13 weeks and 16 modules. The interview block in weeks 10 to 13 and the agentic engineering module already in this track stay as they are. I teach the new module myself.

## New Module 09

Title: Data Pipelines, Freshness and Evaluation Datasets

Topics:

1. Incremental ingestion: add, update and remove documents without rebuilding the index.
2. Freshness: how old the index is, and what the assistant says when its data is stale.
3. Building an evaluation dataset from real questions and documents, with synthetic cases for the gaps.
4. Versioning the evaluation dataset, and updating it when the documents change.

You produce: a pipeline that keeps your assistant's index up to date, with a freshness report, and a versioned evaluation dataset for your project.

Blurb: Most assistants work on the day you load the documents and get worse as the documents change. In this module you keep the data behind your assistant fresh and build the evaluation dataset you use for the rest of the program.

## Merged Module 10

Title: Testing and Evaluating Answers and Agents

You produce: a regression suite running in CI and an evaluation report comparing two configurations.

## Line Edits in Other Modules

Module 02, Retrieval, Document Processing and Indexing. You produce: a one-command ingestion pipeline you can rerun safely and a knowledge assistant with sources.

Module 04, Evaluating Retrieval. You produce: a first evaluation dataset, a retrieval evaluation and a justified configuration.

Module 11, Tracing, Monitoring, Cost and Latency. You produce: traces, dashboards that include data freshness, and a cost and latency report with a measured improvement.

## Outcomes and Final Project

Outcome 2: Use retrieval-augmented generation (RAG) and document processing over company data, and keep the index up to date as documents change.

Outcome 5: Build evaluation datasets from realistic tasks, evaluate answers and tool use, compare prompts and models, and catch regressions.

Final project: You build and deploy an AI assistant for a concrete company use case, for example one that answers questions from messy internal documents that keep changing, with sources and carries out actions after human approval. You show where it works, where it fails, and how you measured that.

The [16 November entry](../entries/2026-11-16.md) has the options I compared and why I chose this shape.
