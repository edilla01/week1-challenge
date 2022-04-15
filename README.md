# Horiseon Code Refactor for Accessibility

## Description

The good folks at Horiseon tasked me to refactor their homepage to include enhancements for accessibility and best practices.

Lastly, if your project is deployed, include a link to the deployed application here.

If you're new to Markdown, read the [GitHub guide on mastering markdown](https://guides.github.com/features/mastering-markdown/).

If you need an example of a good README, check out the [VS Code GitHub repository](https://github.com/microsoft/vscode).


## Table of Contents (Optional)

If your README is very long, add a table of contents to make it easy for users to find what they need, such as the following:

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)


## Installation

What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running.


## Usage

Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

```md
![alt text](assets/images/screenshot.png)
```


## Credits

List your collaborators, if any, with links to their GitHub profiles.

If you used any third-party assets that require attribution, list the creators with links to their primary web presence in this section.

If you followed tutorials, include links to those here as well.


## License

The last section of a good README is a license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, use [https://choosealicense.com/](https://choosealicense.com/)


---

🏆 The sections listed above are the minimum for a high-quality README, but your project will ultimately determine the content of this document. You might also want to consider adding the following sections.

## Badges

![badmath](https://img.shields.io/github/languages/top/lernantino/badmath)

Badges aren't _necessary_, per se, but they demonstrate street cred. Badges let other developers know that you know what you're doing. Check out the badges hosted by [shields.io](https://shields.io/). You may not understand what they all represent now, but you will in time.

## Features

If your project has a lot of features, consider adding a heading called "Features" and list them there.

## Contributing

At the highest level, I changed the file structure so that the index.html file was at the topmost level 
I replaced the first top level <div> to use <header> instead and within that, updated the second level <div> to use <nav> instead 
<footer> instead of div
<section> for jumbotron instead of <div>
added <alt> for pictures 
combine css for images in the content class 
combine css for h2 in the content class
combine css for three articles in content class into .content article
deleted class names for three content articles, no longer needed
move all css for content section to be near eachother 
remove css for p bc it defines the font size as 16 px but that's already the default. 

## Tests

Go the extra mile and write tests for your application. Then provide examples on how to run them.

---
© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.

