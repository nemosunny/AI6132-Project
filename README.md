# Introduction

This repository provides the evaluation benchmark designed for the **AI6132 course project**. It is intended for evaluating **Text-to-Video (T2V)** and **Text-and-Image-to-Video (TI2V)** generation tasks.

## Dataset Structure

- `./first_image/` contains the first-frame images used as image conditions for TI2V models.
- `prompts.jsonl` contains the corresponding text prompts for all benchmark samples.

Each image in `./first_image/` can be matched with its corresponding entry in `prompts.jsonl` using the sample filename.
