# Continuous Intelligence

This site provides documentation for this project.
Use the navigation to explore module-specific materials.

## How-To Guide

Many instructions are common to all our projects.

See
[⭐ **Workflow: Apply Example**](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
to get these projects running on your machine.

## Project Documentation Pages (docs/)

- **Home** - this documentation landing page
- **Project Instructions** - instructions specific to this module
- **Your Files** - how to copy the example and create your version
- **Glossary** - project terms and concepts

## Additional Resources

- [Suggested Datasets](https://denisecase.github.io/pro-analytics-02/reference/datasets/cintel/)

## Custom Project

### Dataset
clinal_data_jugurtha.csv - This dataset contains age and height data for adults from a clinic.

### Signals
- **Age** - The age of the adult patients in years.
- **Height** - The height of the adult patients in inches.

### Experiments
- **Anomaly Detection** - Identify any age or height values that are outside of reasonable limits for adults. This could indicate data entry errors or outliers in the dataset.
- **Threshold Used** - For age, we will consider values above 95 years or below 21 years as anomalies. For height, we will consider values above 72 inches or below 60 inches as anomalies.

### Results
4 anomalies were found in the dataset based on the defined thresholds.

### Interpretation
While people aged 96, 102, or 118 could exist, such ages are extremely rare in the general population. For the purposes of my program and learning exercises, these values are flagged as anomalies. Also a person with a height of 73 inches (6 feet 1 inch) is taller than the average adult height, and while not impossible, it is less common, and was added to the anomalies list for this exercise. The goal of this project is to learn how to set thresholds and identify anomalies in static data, so these values are flagged to illustrate the concept of anomaly detection.
