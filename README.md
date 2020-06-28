Oran Collins
============

# TODO
- fix pandoc not finding README.md within docker conatiner
   - possible: use ${{ env.GITHUB_WORKSPACE }}
- migrate to master_resume_v1.md instead of readme.md

# Links
- https://help.github.com/en/actions/configuring-and-managing-workflows/using-environment-variables
- https://github.com/actions/checkout
- https://raw.githubusercontent.com/sdsawtelle/markdown-resume/master/resume.md
- https://github.com/maxheld83/pandoc-action
- https://github.com/pandoc/dockerfiles#available-images
- https://github.com/pandoc/pandoc-action-example
- https://hub.docker.com/r/pandoc/latex/
- https://help.github.com/en/actions/configuring-and-managing-workflows/configuring-a-workflow#referencing-a-container-on-docker-hub
- https://github.com/r-lib/actions/tree/master/setup-pandoc
- https://pandoc.org/demos.html
```
pandoc MANUAL.txt --pdf-engine=xelatex -o example13.pdf
```
- https://github.com/actions/upload-artifact
- https://gist.github.com/wisehackermonkey/1d1ea823ca4225ce254da9ed53ab4b38
- https://itnext.io/how-to-set-up-github-workflows-and-create-github-actions-using-docker-3a5ba7ec0988
- https://help.github.com/en/actions/reference/workflow-syntax-for-github-actions
- https://help.github.com/en/actions/reference/workflow-syntax-for-github-actions#example-using-a-docker-hub-action
- https://github.community/t/environment-variable-github-workspace-unusuable-when-setting-environment-variables/17266/2
-------------------     ----------------------------
1 MyAddress                        oranbusiness@gamil.com
MyTown 1000                          @twitter_handle
MyCountry                           1800 my-phone-nr
-------------------     ----------------------------

Education
---------

2010-2014 (expected)
:   **PhD, Computer Science**; Awesome University (MyTown)

    *Thesis title: Deep Learning Approaches to the Self-Awesomeness
     Estimation Problem*

2007-2010
:   **BSc, Computer Science and Electrical Engineering**; University of
    HomeTown (HomeTown)

    *Minor: Awesomeology*

Experience
----------

**Your Most Recent Work Experience:**

Short text containing the type of work done, results obtained,
lessons learned and other remarks. Can also include lists and
links:

* First item

* Item with [link](http://www.example.com). Links will work both in
  the html and pdf versions.

**That Other Job You Had**

Also with a short description.

Technical Experience
--------------------

My Cool Side Project
:   For items which don't have a clear time ordering, a definition
    list can be used to have named items.

    * These items can also contain lists, but you need to mind the
      indentation levels in the markdown source.
    * Second item.

Open Source
:   List open source contributions here, perhaps placing emphasis on
    the project names, for example the **Linux Kernel**, where you
    implemented multithreading over a long weekend, or **node.js**
    (with [link](http://nodejs.org)) which was actually totally
    your idea...

Programming Languages
:   **first-lang:** Here, we have an itemization, where we only want
    to add descriptions to the first few items, but still want to
    mention some others together at the end. A format that works well
    here is a description list where the first few items have their
    first word emphasized, and the last item contains the final few
    emphasized terms. Notice the reasonably nice page break in the pdf
    version, which wouldn't happen if we generated the pdf via html.

:   **second-lang:** Description of your experience with second-lang,
    perhaps again including a [link] [ref], this time placing the url
    reference elsewhere in the document to reduce clutter (see source
    file). 

:   **obscure-but-impressive-lang:** We both know this one's pushing
    it.

:   Basic knowledge of **C**, **x86 assembly**, **forth**, **Common Lisp**

[ref]: https://github.com/githubuser/superlongprojectname

Extra Section, Call it Whatever You Want
----------------------------------------

* Human Languages:

     * English (native speaker)
     * ???
     * This is what a nested list looks like.

* Random tidbit

* Other sort of impressive-sounding thing you did
