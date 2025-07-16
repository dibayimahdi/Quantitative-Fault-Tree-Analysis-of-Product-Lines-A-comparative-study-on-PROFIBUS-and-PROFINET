This repository contains XFTA (eXtended Fault Tree Analysis) files and related artifacts used in the reliability analysis of train communication networks implemented with PROFIBUS and PROFINET protocols. The analysis focuses on applying fault tree analysis (FTA) techniques in the context of product line engineering (PLE) to evaluate the reliability of different train variants.

Overview
Modern train systems employ complex communication networks for safety-critical and operational purposes. Two widely used communication protocols standardized under IEC 61158 and IEC 61784 are:

PROFIBUS: A classical serial Fieldbus technology.

PROFINET: An industrial Ethernet-based protocol.

This repository provides fault tree models for train data communication networks using both protocols, with a focus on reliability evaluation across different train configurations.

Key Features
Fault Tree Models for PROFIBUS- and PROFINET-based network architectures.

Support for product line engineering, capturing both commonalities and variabilities across train variants.

Quantitative reliability analysis using the XFTA calculation engine, including failure rate evaluations.

Experimental results for:

4-car train

6-car train

8-car train

16-car train

Motivation
In systems such as trains, airplanes, and vehicles, development is rarely done from scratch. Reuse of components and architecture is essential, and PLE helps manage this reuse across a family of products. This repository demonstrates how fault tree analysis can be systematically applied to product families, providing a reliability assessment not just for a single product, but for multiple configurations.
