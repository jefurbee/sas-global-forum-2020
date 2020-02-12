# How to Contribute

We'd love to accept your contributions to this project. There are
just a few small guidelines you need to follow.

## Complete the Contributor License Agreement (non-authors only)

The Contributor License Agreement (CLA) protects you and SAS by ensuring that you grant permission to host your
contributed code in this conference repository.  If you're an author or presenter for SAS Global Forum 2020, then it is
likely that this permission has been addressed in an existing agreement.

Presenters at SAS Global Forum will have already completed a marketing release agreement for their papers and presentations.
**If you're an author/presenter for SAS Global Forum 2020**, you *do not* need to complete
an additional contributor agreement.

**If you're an employee of SAS Institute Inc.**, then you *do not* need to complete an additional
contributor agreement.

All *other* contributors to this repository should submit a signed
[Contributor Agreement](ContributorAgreement.pdf).
You (or your employer) retain the copyright to your contribution,
this simply gives us permission to use and redistribute your contributions as
part of the project.

To proceed, complete the fields in the agreement, sign it, and send a PDF version of the completed agreement to [github@sas.com](mailto:github@sas.com).  Please be sure to include your GitHub account name in the message.

## How to add your own code

We use standard Git and GitHub mechanisms for accepting contributions to this
project.  That means that you will:

1. Fork this project to your own GitHub account, or clone it to a local repository.        (Don't know what we mean by "fork" and "clone"? Check the
   [GitHub glossary](https://help.github.com/articles/github-glossary/) to learn the lingo.)

2. If necessary, create a new subfolder in the [/papers](papers/) folder for your code and other assets.  (We have already created folders and template README.md files for all accepted, contributed papers.) Please name the folder according to the same naming conventions that you used when you submitted your final paper.  That is:

        sessionNumber-YEAR-surname

   For example:

        2822-2020-Smith

3. Use a pull request to submit your new content.  One of the project owners will
   review the change and merge it with the rest of the project.  Reviewers will check only that you have followed the recommended structure (adding/changing content
   in the folder for your paper).  For these contributions,the reviewer is not checking for quality or completeness of the content.  As the paper author, we assume that you know what your readers need.
   
**Do not change or remove** other content that isn't related to your paper.  Although your copy of the repository contains all content, only the changes you add will be merged as part of the pull request.   

Consult [GitHub Help](https://help.github.com/articles/about-pull-requests/) for more information on using pull requests.

If you're new to GitHub and would like to see a walkthrough of a pull request, we recorded a short video (11 min) and [shared in the SAS Global Forum group on SAS Support Communities](https://communities.sas.com/t5/SAS-Global-Forum-2020/SAS-Global-Forum-2020-on-GitHub/gpm-p/614782).

## Types of files you should include

DO contribute these types of files to support your presentation

* A README.md file in the top level folder for your contribution.  The README.md
  should document the other content that you've contributed, and provide a direct
  link to the PDF for your paper in the SAS Global Forum proceedings.  Optionally
  include contact information so that interested readers know how to ask you questions
  or send you lavish praise for your work.
* Source code for SAS programs (\*.sas)
* Jupyter Notebook files (\*.ipnyb), which you can create using SAS University Edition
  or in any SAS environment where you've configured Jupyter Notebook or Jupyter Lab.
* Sample data files THAT YOU HAVE PERMISSION TO DISTRIBUTE.  You can include as CSV
  files, Excel workbooks, or SAS data sets (\*.sas7bdat).
* SAS project files, such as from SAS Enterprise Guide (\*.egp) or flows from SAS
  Enterprise Miner (\*.xml)
* Presentation materials, such as a PDF version of your presentation slides.

## Files you should NOT include

DO NOT include any of the following:

* A copy of your SAS Global Forum paper.  These are provided as part of the proceedings on the SAS Global Forum web site, so don't duplicate that here.  (Exception: if your paper needs to be updated because of an error or new information after the proceeedings are published, you can add errata or a new version here.  Be sure to indicate that it's an updated version.)

* Data files that you don't have explicit permission to distribute.  Note that even public data sets can have special terms of use.  Just because data is "free", that doesn't mean that you're allowed to distribute it.

* Executable programs, like EXEs or DLLs -- anything that is not easily examined.
