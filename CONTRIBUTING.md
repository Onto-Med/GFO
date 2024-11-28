# Contributing Guide

Thank you for investing your time in contributing to our project!

Read our [Code of Conduct](CODE_OF_CONDUCT.md) to keep our community approachable and respectable.

## Issues and Support

If you find a problem or have a question about the content in this repository and how to use it,
please create an issue in the [Issues Tracker](https://github.com/Onto-Med/GFO/issues).
Make sure you describe the problem as clearly as possible.

## Workflow to Make Contributions

We are very happy about contributions!

It is recommended to use an ontology editor such as [Protégé](https://protege.stanford.edu/).
If you want to contribute changes, please do so by:

1. Clone this repository ([fork](https://github.com/Onto-Med/GFO/fork) for external contributors).
2. Creating a new feature branch.
3. Apply your changes.

   Edit the ontology files using a suitable ontology editor or text editor.
   Adhere to the GFO's existing coding style and conventions.
   Ensure your changes are well-documented and understandable.
   You can run the following command with docker to check your changes locally (in this case `modules/gfo-base.owl` is checked):

       docker run -it -v .:/gfo -w /gfo obolibrary/odklite robot report --input modules/gfo-base.owl --profile qc_report/profile.txt

4. Commit and push all changes.
5. Create a [pull request](https://github.com/Onto-Med/GFO/pulls).

   On GitHub, create a pull request from your branch to the main branch of the official GFO repository.
   Provide a clear description of your changes and the rationale behind them.

6. Review and Feedback.

   Be prepared to address feedback and suggestions from the GFO community and maintainers.
   Work collaboratively with other contributors to refine your changes.
