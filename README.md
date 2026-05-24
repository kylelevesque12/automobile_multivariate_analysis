# Latent Structure and Group Differences in Automobile Characteristics

This project applies multivariate statistical methods to the 1985 UCI Automobile dataset to study relationships among automobile price, performance, size, fuel efficiency, and body style. 

This project was completed by Kyle Levesque and Eric Lin for a multivariate statistics course at Yale University. 

## Overview

The goal of this analysis is to understand whether automobile characteristics can be summarized by lower-dimensional latent structure, whether body styles differ in their overall multivariate profiles, and whether automobiles naturally form groups based on quantitative characteristics.

## Methods

- Factor Analysis
- MANOVA / Multivariate GLM
- Multi-Response Permutation Procedure (MRPP)
- Correspondence Analysis
- Non-metric Multidimensional Scaling (NMDS)
- Hierarchical Cluster Analysis

## Main Findings

The analysis suggests that much of the structure in the automobile data reflects a tradeoff between larger, more powerful, higher-priced vehicles and more fuel-efficient vehicles. Body style is meaningfully associated with multivariate automobile profiles, but the ordination results show substantial overlap rather than perfectly separated body-style clusters.

## Files

- `automobile_multivariate_analysis_report.pdf`: Final written report
- `automobile_multivariate_statistical_analysis.Rmd`: R Markdown source file
- `data/automobile.csv`: Automobile dataset used in the analysis

## Data Source

The dataset comes from the 1985 Ward’s Automotive Yearbook and is publicly available through the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/10/automobile).
