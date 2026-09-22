# Biometric System Evaluator — User Guide

## Overview

Biometric System Evaluator is a desktop application for reviewing and comparing biometric system results.

It helps you:

- Import biometric evaluation data.
- View and compare system performance on interactive charts.
- Compare important biometric performance measures.
- Customize how systems and charts are displayed.
- Save charts and calculated results for later use.

The application is designed to make biometric evaluation results easier to explore and compare in one place.

---

## Getting Started

When you open the application, you can import one or more sets of biometric results.

After importing your data, each system appears in the application so you can:

- Show or hide it on the chart.
- Change its appearance.
- Compare it with other systems.
- Review its performance measures.

You can work with several systems at the same time to make comparisons easier.

---

## Application Overview

The application uses a single main screen where you can import systems, explore their results, adjust the chart, and
compare performance measures.

![](assets/Screenshot%202026-09-22%20112909.png)
![](assets/Screenshot%202026-09-22%20113244.png)

---

## Importing Data

You can import biometric evaluation system outputs from CSV, TSV, Excel, and Parquet files. You can import a single file
or several files at once, including files from a folder.

The application recognizes common biometric result formats automatically. During import, you can choose whether the
scores represent **similarity** or **distance**:

- **Similarity:** higher scores indicate a stronger match.
- **Distance:** lower scores indicate a stronger match.

If your files use different column names, you can adjust the column mapping during import.

Each imported file appears as a separate system, so you can compare multiple systems within the same workspace. Large
imports show their progress and can be cancelled while they are running.

---

## Exploring and Comparing Results

The main chart provides an interactive view of biometric system performance. You can zoom and move around the chart,
change its scale, and reset the view when needed.

For each system, you can:

- Show or hide it on the chart.
- Change its color, line style, and line thickness.
- Compare it with other imported systems.

You can also adjust the chart grid and legend to make the results easier to read.

The chart shows how false acceptance and false rejection change as the decision threshold changes, helping you compare
system behavior across different operating points.

---

## Performance Measures

The application provides a comparison table for commonly used biometric performance measures. You can choose which
measures to display and compare multiple systems side by side.

Available measures include:

- **EER (Equal Error Rate)** — the point where false acceptance and false rejection are equal.
- **EER Threshold** — the threshold associated with the EER.
- **AUC (Area Under the Curve)** — summarizes performance across the range of operating points.
- **minHTER** — the minimum half total error rate.
- **TAR at FAR** — the true acceptance rate at selected false acceptance rates.
- **d'** — indicates how well genuine and impostor scores are separated.
- **Sample Counts** — shows the number of genuine and impostor comparisons.

The comparison table can be exported to CSV for further use.

---

## Saving Results

You can save the current chart as a PNG, JPEG, or SVG image. The saved image reflects the systems and view currently
shown in the chart.

For calculated results, you can also save the generated curve data for later use.

---

## Appearance

The application supports both **light** and **dark** themes. You can also choose an accent color and customize the
appearance of individual systems on the chart.

Your appearance choices and window layout are remembered between sessions.

---

## Typical Workflow

1. **Import** one or more biometric result files.
2. **Review** the imported systems in the workspace.
3. **Explore** the performance chart and adjust its view as needed.
4. **Compare** systems using the chart and performance measures.
5. **Customize** the display to make the results easier to read.
6. **Save** charts or comparison results when needed.

## Summary

Biometric System Evaluator provides a single workspace for importing, visualizing, and comparing biometric evaluation
results. It combines interactive charts, performance measures, display controls, and export options so that you can
examine results and compare biometric systems efficiently.
