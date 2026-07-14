# Reliability-Qualified Nighttime Lights for Disaster Shock and Recovery Analysis

This repository contains the reproducible workflow for RQ2 of the VIIRS Black Marble nighttime lights project.

The analysis builds from RQ1, which established that daily nighttime lights in cloud-impacted tropical regions must be reliability-qualified before interpretation. RQ2 uses reliability-qualified NTL to estimate disaster shock, recovery timing, and uncertainty without treating the daily record as continuously observable.

## Repository Scope

This repository supports workflows for:

1. Defining baseline nighttime lights behaviour using RQ1-qualified observations.
2. Detecting disaster shock timing and magnitude relative to baseline.
3. Estimating recovery metrics such as impact drop, T50, T80/T90, recovery slope, and duration below baseline.
4. Comparing DNB-BRDF against gap-filled NTL as a diagnostic check.
5. Attaching observability, interpretability, and uncertainty flags to recovery metrics.

## Core Logic

Observability first.  
Interpretability second.  
Recovery metrics third.

## Data

Raw satellite, settlement, hazard, and electricity-load datasets are not redistributed in this repository.

Local input files should be placed inside `datasets/` following the paths used in the notebooks.

## Workflow

Run notebooks in numerical order.

## License

Code is released under the MIT License unless otherwise stated. Data remain subject to the terms and conditions of their original providers.
