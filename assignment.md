# Assignment: Resume Enhancement with Git, GitHub, and Playwright

Welcome to this unique learning opportunity. This assignment focuses on implementing Git and GitHub for version control and collaboration in a coding project. Here, you'll personalize a pre-existing resume, mirroring a real-world team-based workflow, and getting you ready for future group projects.

## Project Overview

In the tech industry, proficiency in code writing and collaboration on shared codebases is vital. This assignment introduces you to popular collaborative tools like Git, GitHub, and Playwright, underlining their significance in team workflows. You'll work individually, but the assignment is designed to replicate a collaborative workflow.

## Testing with Playwright and Git

Even minor code modifications can sometimes cause unexpected errors or bugs. Automated testing, such as with Playwright, can help mitigate these issues. Playwright is an efficient tool for automating browser tasks, such as form submission, UI testing, and keyboard input. As part of this assignment, you'll use pre-defined Playwright tests to confirm that your modifications don't disrupt the resume's functionality.

## Assignment Workflow

You'll start with a given HTML/CSS resume. Your task is to personalize this resume using Git's branching and pull request workflow while ensuring functionality with Playwright tests.

## Learning Materials
### Videos
- Real-world Examples in Git Command Line Cheat Sheet - [here](git.md)
- VSCode and Commits - [here](https://www.youtube.com/watch?v=E6ADS2k8oNQ)
- VSCode and Branches - [here](https://www.youtube.com/watch?v=b9LTz6joMf8)
- VSCode and Pull Requests - [here](https://www.youtube.com/watch?v=LdSwWxVzUpo)
- Collaborative Git Command-line between Two Students - [here](https://www.youtube.com/watch?v=_wQdY_5Tb5Q)

### Websites
- In-depth Git Tutorial - [here](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud) - Ensure you go through all sections for a complete understanding of collaboration.
- GitHub Flow - [here](https://docs.github.com/en/get-started/quickstart/github-flow)

## Assignment Steps

1. **Initial Setup:** Start by accepting the assignment on GitHub Classroom to create your repository. Clone this repository to your local machine, and initiate your changes in a new branch.
2. **Making Changes:** Modify the resume to meet the requirements of one of the pull requests listed below.
3. **Testing Changes:** After making changes, execute the provided Playwright tests to ensure your modifications do not break the resume's functionality.
4. **Committing Changes:** Once you've confirmed the changes via testing, commit them with clear and descriptive commit messages.
5. **Creating Pull Requests:** After committing your changes, push your branch to the remote repository and create a new pull request via the GitHub page of your repository.
6. **Review and Merge:** Normally, your teammates would review your changes and give feedback. For this assignment, you'll be self-reviewing and merging the pull request after providing comments.
7. **Iteration:** After successfully merging your pull request, switch to the `master` branch and pull the latest updates. For additional modifications, create a new branch and repeat the process.

This assignment aims to give you a real-world experience of using

## Specific Pull Requests for the Assigment  - YOU MUST DO EACH ONE Separatly the purpose is to practice the process, so you can do this in your group without problems.   
1. **PR 1: Update HTML Metadata and Title**
   - **New branch:** `update-html-metadata`
   - **VS Code Steps:** 
     - Open the HTML file and locate the `head` section. Modify the `meta` tags and `title` element to reflect your personal details.
     - Use the Source Control panel on the left to view the changes you made.
     - Select the plus sign to stage your changes.
     - Under "Message", input your commit message: "Update meta description to match personal resume", then press the checkmark to commit your changes.
     - Repeat for the following commit messages: "Include personal skills and job interests in meta keywords" and "Change title to reflect name and job title".
     - Push your changes to GitHub using the ellipsis (...) menu at the top of the Source Control panel, selecting "Push to..." and choosing the `update-html-metadata` branch.
   - **After merging PR:** Use the "Pull (fast-forward)" command from the ellipsis (...) menu at the top of the Source Control panel to update your local repository.

2. **PR 2: Update Personal Details and Profile Picture**
   - **New branch:** `update-personal-details`
   - **VS Code Steps:** 
     - Update your personal details in the `body` section of your HTML, and change the profile picture to your own.
     - Use the Source Control panel on the left to view the changes you made.
     - Stage, commit, and push your changes as before, with the commit messages: "Change name in resume to personal name", "Update job title to reflect personal career interest", "Update career objective", and "Replace profile picture".
   - **After merging PR:** Update your local repository as before.

3. **PR 3: Update Contact Information and Social Links**
   - **New branch:** `update-contact-info`
   - **VS Code Steps:** 
     - Replace the placeholder social media and contact links with your own in the `aside` section.
     - Stage, commit, and push your changes with commit messages such as: "Update LinkedIn link", "Update Twitter link", "Update GitHub link", "Update email address", and "Update phone number".
   - **After merging PR:** Update your local repository as before.

4. **PR 4: Customize Skills**
   - **New branch:** `customize-skills`
   - **VS Code Steps:** 
     - Modify the skills in the `skills-section` to reflect your own skills and find the correspondinig on font awesome.
     - Stage, commit, and push your changes with commit messages such as: "Add skills in JavaScript", "Add skills in HTML/CSS", "Add skills in Python".
   - **After merging PR:** Update your local repository as before.

5. **PR 5: Update Experience**
   - **New branch:** `update-experience`
   - **VS Code Steps:** 
     - Modify the `experience-section` to reflect your own work experience.
     - Stage, commit, and push your changes with commit messages such as: "Add experience at [Company Name]", "Add experience as [Job Title]".
   - **After merging PR:** Update your local repository as before.

6. **PR 6: Update Education**
   - **New branch:** `update-education`
   - **VS Code Steps:** 
     - Modify the `education-section` to reflect your own education background.
     - Stage, commit, and push your changes with commit messages such as: "Add [Degree] from [University Name]", "Add graduation date".
   - **After merging PR:** Update your local repository as before.

7. **PR 7: Add Projects**
   - **New branch:** `update-projects`
   - **VS Code Steps:** 
     - Modify the `projects-section` to add your own projects.
     - Stage, commit, and push your changes with commit messages such as: "Add [Project Name] project", "Add description for [Project Name]".
   - **After merging PR:** Update your local repository as before.

8. **PR 8: Add Certifications**
   - **New branch:** `update-certifications`
   - **VS Code Steps:** 
     - Modify the `certifications-section` to add your own certifications.
     - Stage, commit, and push your changes with commit messages such as: "Add [Certification Name] certification", "Add date for [Certification Name]".
   - **After merging PR:** Update your local repository as before.

9. **PR 9: Update Layout and Styles**
   - **New branch:** `update-styles`
   - **VS Code Steps:** 
     - Change the layout and CSS styles to suit your personal taste.
     - Stage, commit, and push your changes with commit messages such as: "Update layout to [layout style]", "Change primary color to [color name]", "Update font to [font name]".
   - **After merging PR:** Update your local repository as before.

10. **PR 10: Update README and Remove Old Content**
    - **New branch:** `update-readme`
    - **VS Code Steps:** 
      - Update the README file with screenshots of your completed resume (PDF, Mobile, Desktop views), and remove the old content.
      - Use the Source Control panel on the left to view the changes you made.
      - Stage, commit, and push your changes as before, with the commit messages: "Screenshot of Commit Hisory with at least 10 commits ","Remove old README content", "Add screenshots of completed resume".
    - **After merging PR:** Update your local repository as before.
