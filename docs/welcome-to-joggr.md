<!--@@joggrdoc@@-->
<!-- @joggr:version(v2):end -->
<!-- @joggr:warning:start -->
<!-- 
  _   _   _    __        __     _      ____    _   _   ___   _   _    ____     _   _   _ 
 | | | | | |   \ \      / /    / \    |  _ \  | \ | | |_ _| | \ | |  / ___|   | | | | | |
 | | | | | |    \ \ /\ / /    / _ \   | |_) | |  \| |  | |  |  \| | | |  _    | | | | | |
 |_| |_| |_|     \ V  V /    / ___ \  |  _ <  | |\  |  | |  | |\  | | |_| |   |_| |_| |_|
 (_) (_) (_)      \_/\_/    /_/   \_\ |_| \_\ |_| \_| |___| |_| \_|  \____|   (_) (_) (_)
                                                              
This document is managed by Joggr. Editing this document could break Joggr's core features, i.e. our 
ability to auto-maintain this document. Please use the Joggr editor to edit this document 
(link at bottom of the page).
-->
<!-- @joggr:warning:end -->
# Summary

Hello, welcome to Joggr! 😀 We ([Zac](https://www.linkedin.com/in/zacrosenbauer/) and [Seth](https://www.linkedin.com/in/sethrosenbauer/)) started Joggr, because we have a love/hate relationship with documentation. We love the benefits but hate the time required to do it well! In short, we built Joggr for people like us, software developers.

**What is Joggr?**

Joggr is an internal knowledge base for software developers. Joggr integrates directly with GitHub and your IDE (COMING SOON) and automatically maintains the documentation for you. We support everything from code documentation to how-to guides and diagrams. If there is a use case we currently do not support, please let us know.

**What is Joggr for?**

Joggr is meant for software developers who are writing **internal** technical documentation. Other documentation platforms like confluence or notion are used by folks in Operations, HR, and more. Our focus is **on software developers** and building for their use cases.

# Getting Started

To onboard and start using Joggr, you only need to complete two steps:

1. Install our GitHub App

2. Sign-Up

To onboard, go to [app.joggr.io](app.joggr.io) and follow the instructions to install our GitHub app and sign up. This should take **\~3-5 minutes**. If you're having any trouble, please reach out to us on your company's Slack channel or email our CEO Seth at <seth@joggr.io>.

Once, you completed the onboarding, check out our video tutorials that will help you get started with importing existing documentation, creating documentation, and organizing documentation on Joggr.

# Video Tutorials

Watch the videos below to learn more about how we use Joggr @ Joggr 😀 If you are looking for more help, please reach out to us in your company's slack channel or email Seth directly at <seth@joggr.io>

## How to Import Existing Documentation

Watch the video below to learn how to import existing GitHub markdown into Joggr. When you import GitHub markdown to Joggr, we create a Pull Request. [Here ](https://github.com/joggrdocs/support/pull/1)is an example of what this will look like and why Joggr does this. **Please make sure to merge this pull request**, so that you do not run into merge errors (this would only occur if you leave this pull request open for a long time and there are conflicts).

If you're looking for help importing documents from Confluence, Notion, Google Drive, or other platforms, please reach out to the Joggr team and we will assist.

[Real World Example: Importing existing GitHub Markdown - Watch Video](https://www.loom.com/share/d03d211fc2e941d392d3899931e60ddc)

![](https://cdn.loom.com/sessions/thumbnails/d03d211fc2e941d392d3899931e60ddc-1708038436059-with-play.gif)

## How to create documentation in Joggr

Watch the video below from our CTO as he walks through how to create documentation using Joggr.

[Real World Example: Creating a How-to Guide - Watch Video](https://www.loom.com/share/0f2809f337c1428c9ba623dc79a1e7bb)

![](https://cdn.loom.com/sessions/thumbnails/0f2809f337c1428c9ba623dc79a1e7bb-1708037476848-with-play.gif)

## How to organize documentation in Joggr

Watch the video below from our CTO as he walks through how to organize documentation. Getting this right is very important so that developers can easily find what they need without asking others.

If you need help on how to think about this, please reach out to the Joggr team and we can provide examples of what other teams have done. Watch the video below to see an example of how we set up our directory structure.

[Real World Example: Organizing Documentation at Joggr - Watch Video](https://www.loom.com/share/bc69947b2446491bb11d17efaf7b4a21)

![](https://cdn.loom.com/sessions/thumbnails/bc69947b2446491bb11d17efaf7b4a21-1707529930497-with-play.gif)

# Common FAQs

**Top FAQs**

1. Can you update the documents in GitHub, and IDE, or do all changes need to occur in Joggr?

## Where in GitHub is the document saved?

## How does Joggr maintain the document?

## Can you update the markdown file in GitHub?

Yes, you can make changes to the markdown file in your IDE, GitHub, or Joggr. If you are making edits to the document in your IDE or GitHub, do not do any of the following or it will break Joggr's connection to this document:

* Do NOT change anything in the Header, specifically anything above `<!-- @joggr⚠end -->`

* Do NOT change anything in the Footer, specifically, anything below `<!-- @joggr:editLink(558d484d-9fc2-41d1-9321-c31093e9946c):start -->`

* If you added code snippets to the document using Joggr, do NOT change these code snippets.

For these reasons, we recommend making all updates in Joggr, so that Joggr can keep the connection to this document, which is how we help maintain the document.

## How do you delete a document?

To delete a document, click on the ellipsis in the top right corner of a document and click "Delete". This will only delete the document from Joggr, it does not delete the document in GitHub. If you want to delete the document in GitHub, go to GitHub and delete the document. When you delete a document from GitHub, Joggr automatically deletes the document in Joggr.

## What happens when I move documents in Joggr? GitHub?

In Joggr, feel free to move documents into any directory that you desire. Moving documents between directories in Joggr will have zero impact on where this is stored in GitHub.

If you move a document (.md) file in GitHub that also exists in Joggr, there will be no issue. However, there is one edge case we currently do not support. If you move a GitHub .md file to another location in GitHub AND rename it at the same time, this will cause the Joggr "link" to the document to break. We use this link to help maintain the document. Please reach out if you have any questions on this edge case.

## Is there an audit history?

Yes, there is an audit history. Joggr is built on top of GitHub. Every JoggrDoc created is committed to GitHub as a markdown file. Therefore, you can manage the audit history just like you do with your codebase 😀 [Here](https://docs.github.com/en/repositories/working-with-files/using-files/viewing-a-file#viewing-the-line-by-line-revision-history-for-a-file) is GitHub's documentation on how to view the history of a file.

# Need Help?

If you are looking for more help, please reach out to us in your company's slack channel or email Seth directly at <seth@joggr.io>

<!-- @joggr:editLink(d7a40021-0c3b-4be0-ac2d-f86affb84027):start -->
---
<a href="https://app.joggr.io/app/documents/d7a40021-0c3b-4be0-ac2d-f86affb84027" alt="Edit doc on Joggr">
  <img src="https://cdn.joggr.io/assets/static/badges/joggr-document-edit.svg?did=d7a40021-0c3b-4be0-ac2d-f86affb84027" />
</a>
<!-- @joggr:editLink(d7a40021-0c3b-4be0-ac2d-f86affb84027):end -->