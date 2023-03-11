# github actions gitmoji

To use this tool, simply add it to your Github repository and configure it to check for emoji in your PR titles. Once set up, the tool will automatically check each PR title and provide feedback if it does not contain an emoji. This can be a useful way to ensure that your PR titles are consistent with the Gitmoji convention and can help to improve the overall quality of your code.

To validate cases where emojis are written as text, such as ":memo:", this Github Action checks that the title of the PR starts with ":". This allows for the detection of emojis written in text format and ensures adherence to the Gitmoji convention.
