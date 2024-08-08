# Analyzing the Distribution of Mental Health Professionals and Facilities

Authors: Nuoya Wang, Bernice Yuan, Yunnie Yu

## Introduction

### Background

The mental health crisis in the United States, particularly among college students, has reached alarming levels. Suicide is the second leading cause of death for college students, with approximately 1,100 suicides occurring on college campuses each year. National statistics reveal that 25% of individuals know someone who has died by suicide, and 40% know someone who has attempted suicide. These figures highlight the pressing need for accessible mental health services.

### Purpose

Given these statistics, it is crucial to examine the distribution of mental health professionals across the United States to ensure adequate support is available. This project focuses on analyzing the distribution of mental health professionals across 16 states in the U.S. Using data from the Area Health Resources Files (AHRF) 2022-2023, this study aims to provide insights into the availability and distribution of mental health services. By understanding the distribution of mental health professionals, we can identify gaps in service provision and advocate for policies that enhance access to mental health care. This project is motivated by the urgent need to address the mental health crisis and reduce the incidence of suicide, particularly among vulnerable populations like college students.

### Objectives

The primary objectives of this exploratory analysis are to:
1. **Assess the Distribution of Mental Health Professionals**: Understand how counselors and psychologists are distributed across different states and their various subcategories.
2. **Identify Gaps and Opportunities**: Highlight areas with potentially inadequate mental health resources to guide policy decisions and resource allocation.
3. **Correlate Workforce Distribution with Outcomes**: Explore the relationships between the distribution of mental health professionals and various factors such as population size, median wage, and state policies.


## Usage

To run this project, you need to have R and RStudio installed on your system. The necessary libraries needed for this project are:

```r
# Load the necessary libraries
library(tidyverse)
library(dplyr)
library(ggplot2)
library(readr)

# Load the dataset
data <- read_csv("ahrfsn2023.csv")

# Example analysis
summary(data)
