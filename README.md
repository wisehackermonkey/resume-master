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
