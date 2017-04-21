# How to contribute
First of all, thank you very much for contributing.

Since this project contain mainly static non code files, there is no conventions to follow regarding to the syntax

## Index
1. [Suggest a Topic](#suggest-a-topic)
1. [Suggest a Modification](#suggest-a-modification)
1. [Modify a Comparison](#modify-a-comparison)
1. [Structure of the comparisons](#structure-of-the-comparisons)
1. [Add a comparison](#add-a-comparison)
1. [Rules for Pull Requests](#rules-for-pull-requests)

## Suggest a Topic
If you want to suggest a topic, just create an issue with that request, even if you are uncertain in how to implement it, after the issue is created another person would do the comparison. Only software-related topics will be consider.

## Suggest a Modification
If you consider a comparison is incomplete or miss a key feature or an important candidate was forgotten, you can create a pull request with the suggested changes or create an issue named "Modify" + filename + reason

## Modify a Comparison
If you are willing to add any piece of information you consider necessary, do not hesitate in creating a pull request. Be careful with the style, there is no standard style guide apart from consistency within the files

## Structure of the comparisons
The standard structure is the following:

- Description
- Index with hyperlinks
- Scenario chosen for the analysis
- Set of features to be considered
- Prior requirements to be evalutated (Optional) (*)
- List of candidates
- Evaluation (**)
- Summary by feature
- Summary Table

\* For example in a freeware only comparison, paid software will be list but not evaluated. This is so because the user should know all the options avaiable even if some are not evaluated.

\** If there is a feature just one candidate has, it can be mentioned as a "Special Note" if the feature is important to the analysis, it should be add to the considered features

### Rules for comparisons
- Description have to be brief and concrete
- The Scenario has to be relevant to the general audience
- All possible candidates should be list even those that do not meet the criterion to be evaluated
- Discontinuated candidates should be list and not evaluated even if they meet the criterion
- In the evaluation all features has to be considered and listed
- Each candidate must be provided with the corresponding name and link to offical page
- The summary table must be consistent across files, candidates as coloums and features as rows, the :x: emoji and the ✔ character must be used be used (*)

\* This [web page](http://www.tablesgenerator.com/markdown_tables) is suggested for the creation of the tables

## Add a comparison
Comparisons can fall in one of two categories, structured or unstructured. 

### Add a structured comparison
If you are willing to add any piece of information you consider necessary, do not hesitate in sending a pull request. You have to follow the structure and the pull request rules in order to get your changes merged

### Add an unstructured comparison
In case your comparison does not follow the structured showed above, add the " raw_ " prefix to your file. Example: " raw_online_IDEs.md ". And create and issue named "Structurize" + "filename"

## Rules for Pull Requests
- Each file must have md extension
- Each file must use either pure markdown or mix markdown with html as long as it renders correctly in the github viewer
- Each topic must be self-contain in a single markdown file
- If the file is not structurize a " raw_ " prefix must be added
- Do not create folders or subfolders
- Pull Request with more than one file must follow the multifile pull request rules

### Rules for Multifile Pull Request 
The only reasons why multifile pull request are merged are:

- Fix Typos
- Fix Links
- Add/Fix Images
