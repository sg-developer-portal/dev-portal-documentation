## Overview

In this walkthough, we will be attempting to publish a documentation named My First Documentation as an example, which is located in the collection **Technologies** and 
sub-collection **Analytics**.

<figure style="text-align: center">
  <img
    src="assets/img/page-creation.png" width="80%" height="80%" 
    alt="Fig 1: Master code view in GitHub"
  />
  <figcaption>Fig 1: Master code view in GitHub</figcaption>
</figure>

Step 1: Create a new branch to work on. This branch will contain all the work you will be doing.

<figure style="text-align: center">
  <img
    src="assets/img/page-creation-step-1.png" width="80%" height="80%" 
    alt="Fig 2: Creating a new branch."
  />
  <figcaption>Fig 2: Creating a new branch.</figcaption>
</figure>

Step 2: Uploading images to *'/assets/img/'*. Navigate to the directory and upload your files. Name the image files in this naming convention: product-name-alise.png 
(e.g. my-first-documentation-analytics-dashboard.png).

<figure style="text-align: center">
  <img
    src="assets/img/page-creation-step-2.png" width="80%" height="80%" 
    alt="Fig 3: Uploading images to GitHub."
  />
  <figcaption>Fig 3: Uploading images to GitHub.</figcaption>
</figure>

Step 3: After uploading the necessary images required for your documentation, commit the change into the branch.

<figure style="text-align: center">
  <img
    src="assets/img/page-creation-step-3.png" width="80%" height="80%" 
    alt="Fig 4: Committing new images into the branch."
  />
  <figcaption>Fig 4: Committing new images into the branch.</figcaption>
</figure>

Step 4: Next, navigate to the designated folder you have been informed of. The directory will be in the format '*/collections/[COLLECTION_NAME]/[SUB-COLLECTION_NAME]'*. In this example it would be *'/collections/\_technologies/analytics'*.

<figure style="text-align: center">
  <img
    src="assets/img/page-creation-step-4.png" width="80%" height="80%" 
    alt="Fig 5: Navigating to designated folder."
  />
  <figcaption>Fig 5: Navigating to designated folder.</figcaption>
</figure>

Step 5: Add a new file, which will contain the documentation. Name your documentation [DOCUMENTATION_NAME].md (e.g. gowhere-suite.md). The file name shall be in lower case, and spaces separated by hyphens.

<figure style="text-align: center">
  <img
    src="assets/img/page-creation-step-5.png" width="80%" height="80%" 
    alt="Fig 6: Creating a new markdown file."
  />
  <figcaption>Fig 6: Creating a new markdown file.</figcaption>
</figure>

Step 6: In the documentation, you will have to include both front matter and content. Here is an example of a front matter, where you have to make changes to the
**title**, **category** and **description**.

The title is essentially your product name, follow by your product tagline (e.g. product name - product tagline). The category is the sub-collection that is tagged to your
product and the description should include a summary of your product (not more than 160 characters) as this will give readers an overview of your product on the overview
page before readers click into your product page.

"---"<br />
"title: My First Documentation"<br />
"layout: layout-page-sidenav"<br />
"category: Analytics"<br />
"description: >"<br />
"  My First Documentation is..."<br />
"---"

<figure style="text-align: center">
  <img
    src="assets/img/page-creation-step-6.png" width="80%" height="80%" 
    alt="Fig 7: Markdown file content"
  />
  <figcaption>Fig 7: Markdown file content</figcaption>
</figure>

Step 7: For videos, please ensure videos are uploaded to Youtube before embedding the video into your documentation. Use the code below to embed your video.

```
<iframe src="https://www.youtube.com/embed/<video-id>?showinfo=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```
<br />

Step 8: Commit the changes once done, into the branch.

<figure style="text-align: center">
  <img
    src="assets/img/page-creation-step-8.png" width="80%" height="80%" 
    alt="Fig 8: Committing new md file into the branch."
  />
  <figcaption>Fig 8: Committing new md file into the branch.</figcaption>
</figure>

Step 9: You will have to link the documentation to the left navigation bar for easy navigation. Head over to *'/\_data folder'*. Locate the collection you were designated
(in this case, technologies.yml), and open it. This is a YAML configuration file which you will have to edit.

<figure style="text-align: center">
  <img
    src="assets/img/page-creation-step-9.png" width="80%" height="80%" 
    alt="Fig 9: Content in technologies.yml file."
  />
  <figcaption>Fig 9: Content in technologies.yml file.</figcaption>
</figure>

Step 10: Add in the name of the documentation (e.g. My First Documentation) you are intending to publish. Adding the documentation to the list of items will allow it to
render a link which displays my-first-documention.md created previously.

<figure style="text-align: center">
  <img
    src="assets/img/page-creation-step-10.png" width="80%" height="80%" 
    alt="Fig 10: Updating technologies.yml."
  />
  <figcaption>Fig 10: Updating technologies.yml.</figcaption>
</figure>

Step 11: Commit the changes as usual into the branch.

Step 12: Create a pull request from your branch into master

<figure style="text-align: center">
  <img
    src="assets/img/page-creation-step-11.png" width="80%" height="80%" 
  />
</figure><br />

<figure style="text-align: center">
  <img
    src="assets/img/page-creation-step-12.png" width="80%" height="80%" 
    alt="Fig 12: Creating a pull request."
  />
  <figcaption>Fig 12: Creating a pull request.</figcaption>
</figure>

Step 13: Head over to the pull request, and click on the check provided by *'AWS Amplify Console'*. You will be redirected to a webpage containing a link to the preview site.
Click on the link and you should see a preview version of the Dev Portal which includes your documentation.

Should you not be satisfied with the content, edit the documentation from Step 6 and commit again once done. The pull request will be updated automatically and a
new preview link will be available.

<figure style="text-align: center">
  <img
    src="assets/img/page-creation-step-13.png" width="80%" height="80%" 
  />
</figure><br />

<figure style="text-align: center">
 <img
    src="assets/img/page-creation-step-13-1.png" width="80%" height="80%" 
    alt="Fig 13: Previewing the new documentation."
  />
  <figcaption>Fig 13: Previewing the new documentation.</figcaption>
</figure>

Step 14: Once you are satisfied with the page, you can request a review from your teammates who have access to this GitHub repo or you can request a review from the content-approver team (candyyap-gvt and HazelKoh12) to review the content.

<figure style="text-align: center">
  <img
    src="assets/img/page-creation-step-14.png" width="80%" height="80%" 
    alt="Fig 14: Requesting for approval."
  />
  <figcaption>Fig 14: Requesting for approval.</figcaption>
</figure>

Step 15: Once the review is approved, send an email to content-approver to publish the content. Once published, your changes will go live. Congratulations! You have just published your first documentation successfully.

<figure style="text-align: center">
  <img
    src="assets/img/page-creation-step-15.png" width="80%" height="80%" 
    alt="Fig 15: Documentation page in Dev Portal"
  />
  <figcaption>Fig 15: Documentation page in Dev Portal</figcaption>
</figure>


