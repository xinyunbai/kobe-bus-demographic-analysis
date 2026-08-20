# Kobe Bus Demographic Analysis

This repository contains the analysis results for a Kobe City public transport PBL project.

## Project Overview

The study examines whether current bus service supply in Kobe City is aligned with recent demographic changes.

The analysis combines:

- Population data from July 2019 and July 2026
- Current 2026 GTFS bus service data
- Kobe City administrative boundary GIS data

The analysis consists of two phases:

### Phase 1: Identify Priority Areas

Population characteristics and current bus service supply are combined to calculate an exploratory Need–Supply Mismatch Index.

The main priority areas identified are:

1. Nishi Ward
2. Kita Ward
3. Tarumi Ward
4. Higashinada Ward

### Phase 2: Resource Allocation Optimization

A preliminary mathematical optimization model is used to examine how limited additional bus-service resources could be allocated across wards.

Under the illustrative 10-resource-unit scenario, the allocation is:

- Nishi: 4
- Kita: 4
- Tarumi: 2

The resource units are standardized illustrative service packages and do not directly represent buses, stops, or routes.

## Interactive Map

The interactive map visualizes ward-level demographic and bus service information in Kobe City.

GitHub Pages:
https://xinyunbai.github.io/kobe-bus-demographic-analysis/

## Data Files

The repository includes:

- Bus stops with ward information
- Ward-level demographic and bus service analysis
- Priority ranking results
- Sensitivity analysis
- Analysis metadata

## Analysis Environment

Python on Google Colab

## Notes

GTFS represents scheduled service supply, not observed passenger demand.

This project is an exploratory PBL analysis intended to support identification of priority areas for further public transport review.
