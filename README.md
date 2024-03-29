# Guide for Hosting Your Resume on GitHub Pages

## Purpose

This document aims to outline the actionable steps for creating and hosting a resume in Markdown format via GitHub pages, and to connect these steps with the principles of contemporary Technical Writing as potrayed in Andrew Etter's Modern Technical Writing.


## Pre-requisites

Before we dive into the hosting process, ensure you have the following:

1. **GitHub Account**: Your digital showcase platform. Create your account 
    * Useful blog to get you familiar with Github and its uses: [*What is GitHub?*](https://kinsta.com/knowledgebase/what-is-github/).
    * Create your free account here:  [Join Github!](https://github.com/join)

2. **Markdown-Formatted Resume**: Your resume in Markdown format. Markdown allows for easy formatting and is highly recommended for its simplicity. Here is my [resume](index.md) in Mark down. If you're new to Markdown, there are a lot resources availble to help you get started, check out [More Resources](#more-resources) for links to tutorials, free Markdown editors and more.


## Instructions 

### 1. Creating Your GitHub Repository

- **Step by step instructions**:
  1. Sign in to your GitHub account using your credentials: [login](https://github.com/login).
  2. On your GitHub dashboard, click "New" to create a new repository.
  3. Name it `[YourGitHubUsername].github.io` to automatically generate a web page URL.
  4. Opt for a **Public** repository to showcase your resume to the world.
  5. Select **Add a README file** to set up a README file to give visitors an overview of your repository.

***Linking to Etter's key principals***: GitHub uses Git's smart tracking system to help you keep everything, from code to notes, all in one spot. Etter explains in his book how this setup not only makes team work smoother but also keeps a neat record of all changes. This is super handy for fixing bugs and making sure everything stays up to date. Plus, it's cool because you can work on your stuff without being online, and later mix it back into the main project, letting you and your team tackle different tasks at the same time.

### 2. Adding Your Resume

- **Step by step instructions**:
  1. In your repository, go to "Add file" > "Create new file"
  2. Name the new file `index.md`. It is important that you use 'index.md' as file name because it's the first thing people will see when they visit your site. Think of it as the cover of your resume book.
  3. Use Markdown to format your resume. You can do it directly on GitHub or use an editor listed in: [More Resources](#more-resources.
  4. Select "Commit changes" to save the changes to your repository.

***Linking to Etter's key principals***: Markdown is super easy to use, almost like jotting down notes in plain text but with a few simple tricks to make it look good. Etter highlights how using such a simple system for writing things down means you spend less time worrying about how it looks and more on what you're actually saying. That's why we're going to put your resume online using Markdown. It makes everything straightforward so you can focus on showcasing your skills and experiences without fussing over complex formatting.

### 3. Personalizing Your Page with Jekyll theme

- **Step by step instructions**:
  1. In your repository, go to "Add file" > "Create new file"

  2. Name this new file `_config.yml` file to your respository, this will be used to add theme for your resume
  
  3. Specify your chosen theme, e.g., `theme: jekyll-theme-Merlot`. This is my [config file](_config.yml)

***Linking to Etter's key principals***: In Andrew Etter's perspective, utilizing Jekyll themes through GitHub Pages offers an accessible route to crafting a unified and attractive online presence. He emphasizes the importance of delivering technical content in an aesthetically pleasing manner for enhanced reader engagement. Essentially, leveraging these themes simplifies the process of establishing a professional-looking static website.

### 4. Publishing Your Resume

- **Step by step instructions**:
  1. Navigate to "Settings" > "Pages" from the menu on the left side in your repository.
  2. Choose the option "Deploy from a branch" in the Source section.
  3. Pick the "main" branch and set the directory to "/ root". This step is crucial because it tells GitHub Pages exactly where to look for your resume file at the heart of your project.
  4. Wait for a few minutes to let GitHub build your static website.
  5. Congratulations, your professional resume is now hosted at `https://[YourGitHubUsername].github.io/` 

***Linking to Etter's key principals***: Andrew Etter highlights the critical role of easy access and direct deployment in managing technical documents. By embracing his recommendations, we use GitHub Pages, a built-in service of GitHub, to create static websites. This strategy ensures our resume is readily accessible online, simplifying updates and management, thereby streamlining the presentation and maintenance of our professional details.

## Gif
![gif](https://github.com/hridaimehta/hridaimehta.github.io/blob/main/assets/Resume-Gif.gif)
   My resume hosted on the static website. 
   
## More Resources
* [What is GitHub?](https://kinsta.com/knowledgebase/what-is-github/): A great resource for introduction of GitHub to a biginner.
* [Tutorial](https://www.markdowntutorial.com/): Free tutorials and practice quizzes.
* [Dellinger](https://dillinger.io/): Free online Markdown Editor.
* [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/): A quick reference to the Markdown syntax..
* [Jekyll Themes for GitHub](https://pages.github.com/themes/): Jekyll themes that work out of the box with GitHub pages.


## Acknowledgements
I want to extend my sincere thanks to Andrew Etter for sharing their expertise on Technical Writing through their publication, Modern Technical Writing. I'm also grateful to my team members, Vishal Singh Heer and Simran Kaur, for their constructive feedback and contributions that enhanced the quality of this document. Finally, I'd like to thank our professor, Stewart Wilcox, for their support and guidance in bringing this project to fruition!

## FAQs

**Q: What makes Markdown the preferred choice for crafting a resume?**
   - A:  Markdown's simplicity and ease of use make it perfect for creating resumes. It allows you to focus on your content without worrying about complex formatting, ensuring your resume looks polished and professional.

**Q: I've followed all the steps, but my resume still isn't visible on GitHub Pages. What's next?**
   - A:
     - Double-check that your repository's name matches the [YourGitHubUsername].github.io format.
     - Confirm that your index.md file is correctly using Markdown and is located in the repository's root.
     - Lastly, revisit your GitHub Pages' settings to ensure everything is set up properly. If issues persist, GitHub's help documentation or community forums are great places to seek further assistance.
