### Introduction

This repo aims to compress the input to fit the input to a transformer.

### Example

The limit for gpt 4 model is around 8000 tokens.
If our input is 10000 tokens we need to compress it to 8000 tokens and then input it to the model.

### Possibilites

For a music or text generator architecture with fixed input limit, we can input the time series data by compressing it over and over again.
