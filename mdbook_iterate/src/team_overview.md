
<!-- toc -->

# Web Development Teams Overview

Iterate website Define, Design, Develop, Deploy and Maintenance teams may be operational at the same time creating, testing, and helping with maintenance  

<div style="text-align: center;">
<b>Teams</b>

``` mermaid
	graph TD
    dev --- def
    dev --- des
    dev --- dep
    dev --- mnt
    def --- des
    dep --- mnt

    dev([Development])
    def([Define])
    des([Design])
    dep([Deploy])
    mnt([Maintenance])
```

<b>Iterative Development Teams</b>

</div>

## Minimum Viable Product

The first goal of an *Iterate Website Development* projects is delivering a Minimum Viable Product.

It is a way of understand whether the website project idea will work or not. It is a stage in website development where the **Must** features are implemented and ready to test with users. It gives feedback about the positive aspects and shortcomings.

The next steps are adding the **Want** features, until Stakeholders agree the website is production quality and ready to be deployed.

 ---
 
## Private Preview Website

Each team member has a GitHub account and has [cloned](git.md#clone) a copy fo the Central Project Repository to their workstation

Changes made to the local cloned repositories cannot directly affect the Central Project Repository. It is managed by a *gatekeeper* team member. It requires a [Pull Request Review](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/about-pull-request-reviews) This helps maintain a unified source of truth for project history and files.

Team members can create a Preview Website on their workstation created when team members makes changes to their Local Website Repository. They may deploy a [Private Preview Website](preview.md) for themselves and Stakeholders to quickly view and give feedback. 

---

[Private Preview Website](preview.md) created by a [Content Delivery Network](cdn_deploy). 

---

When team members and Stakeholders agree  changes are ready to be added to the Production Website,  team members  makes a [GitHub](github.md) [Send Pull Request](https://www.w3schools.com/git/git_remote_send_pull_request.asp?remote=github)

The repository guardian and other team members evaluating Central Website Repository Pull Requests, may deploy a [Private Preview Website](preview.md) for Stakeholders holders to preview and give feedback.


## Repository Guardian Preview

When the repository guardian and other team members evaluating Central Website Repository update requests changes are ready for deployment, the repository guardian deploys the updated production version of the website to a [Private Preview Website](preview.md) for Stakeholders to preview and give feedback. When the Stakeholders are satisfied with the updated preview production version, the repository guardian deploys the updated production version of the website to the Internet 

## Teams Preview
- [[team_define |Team Define]]  
  Defining websites helps the Iterative Development teams and Stakeholders to understand the project.

- [[team_design | Team Design]]  
  Determines the core foundations of user's website experience.

- [[team_develop | Team Develop]]  
  Translates the Define and Design teams processes into website pages 

- [[team_deploy | Team Deploy]] 
  Deploys the website making it available on the Internet. The production version is deployed when Stakeholders agree.

- [[team_maintenance | Team Maintenance]]  
  Remediates the Define, Design, Develop, Deploy, or Security teams defects

