Lab 5 - Collaborative Coding
================

# Part 1 - Run R Markdown through GitHub

In this part of the lab, we will write an R Markdown document and render
it to HTML. We will look at how to keep the first Markdown file,
figures, what to commit to Git and push to GitHub. If GitHub is the main
hosting venue, we render directly to GitHub floavoured Markdown and
avoid the need to create HTML.

## Hello World!

We’ll practice with RStudio’s boilerplate R Markdown document.

Launch RStudio in a Project that is a Git repo that is connected to a
GitHub repo.

We will test our system’s ability to render the \`\`hello world” of R
Markdown documents.

Do this: *File \> New File \> R Markdown..*

- Give the file an informative title.
- Accept or change the default author if you wish
- Accept the default output format of HTML
- Click OK

Save this document to a reasonable filename and location. The filename
should end in .Rmd or .rmd. Save in the top-level of this RStudio
project and Git repository, that is also current working directory.

You might want to commit here. So you can see what’s about to change.

Click on \`\`Knit HTML”. RStudio should display a preview of the
resulting HTML. Also look within the files browser. You should see the
markdown document and the resulting HTML.

## Push to GitHub

Push the current state to GitHub.

Check your files on GitHub on the browser.

Are the new files visible? This should be an R Markdown document and the
associated HTML. Visit both of these in the browser. Check:

- Rmd is readable, but there is no output.
- The HTML looks ugly.

## Formatting the output

In order to display our HTML output in GitHub, we have to specify a
special format of output to GitHub. We can either provide the Markdown
only file (more of which you can read about in the Happy Git with R
notes), or change an instruction in our YAML at the top of our Markdown
document. Simply change the output to be of the form
`output: github_document` as shown below.

``` r
---
title: "My Report"
author: "Craig Alexander"
date: "2024/02/15"
output: github_document 
---
```

Now save your document and commit here.

Render once again using \`\`Knit HTML”.

If you look in the file browser, you will now see updated versions of
your files, including the new .md files. Commit here once again.

## Push to GitHub

Push the current state to GitHub. Go check this in the browser.

- Visit the .md file and compare this to the previous HTML file.
- You should now see your rendered document as it would appear when
  rendered in R.

## Further Work

Now attempt to edit this document, including some working R code from
previous labs and see if you can render this and commit to GitHub
successfully.
