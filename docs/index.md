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
## Dataset
 The dataset used in this project has the basic structure from the example, with age and height. I have customized this project to include weight and BMI to analyze the anomalies.

 ## Signals
 The main signals used in this project is a combination of age or height or weight or BMI. ANy value that is greater than the MAximum threshold values mentioned for these fields are considered anamolies.

 ## Experiments
 For this experiment, I modified the overall dataset, used different ages, and I set different parameters for each of the fields .

 ## Results
I saved the modified csv and added it as the Input data in the Python file. After running the python file I was able to see results for the number of anomalies in each age range.

## Interpretation
Based on the results generated, an Analyst can easily tell from the results the age range that did not meet the threshold limit by looking at the count from the number of anamolies per range field. From the results generated, this dataset particularly ages 12 and above had greater anamolies than the other ages .
