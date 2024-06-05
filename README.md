# STAR Lab Website

## Template Reference
This lab wesite is created using [Lab Website Template](https://github.com/greenelab/lab-website-template) (see [`CITATION.cff`](CITATION.cff)).

## 👇👇 Template Documentation 👇👇
The documentation for this template can be found here [here](https://greene-lab.gitbook.io/lab-website-template-docs).
 
| Important Parts       | Links                    |
|-----------------------|--------------------------|
| Set up your site      | [link](https://greene-lab.gitbook.io/lab-website-template-docs/getting-started/set-up-your-site)|
| Repo structure        | [link](https://greene-lab.gitbook.io/lab-website-template-docs/basics/repo-structure)|
| Edit pages            | [link](https://greene-lab.gitbook.io/lab-website-template-docs/basics/edit-pages)|
| Citations             | [link](https://greene-lab.gitbook.io/lab-website-template-docs/basics/citations) |

## Code Implementation
This section contains some steps involved to tweak the template, test the website, and preview the website.

### Preview the site
After installing the Docker Desktop, run the following command in the terminl to preview the website:

```bash
./.docker/run.sh
```

### Workaround when failed to preview the site
Sometimes, after changing the sources (doi) for `research` page, it will keep failing to generate the website in the terminal while running the preview commands. One workaround is to delete the `_site` folder, restart the terminal and then run the site previewing commands (see above) again. 

## Repository navigation
Some important sections for customizing the lab website is listed below:
    .
    ├── _cite           
    ├── _data
    │   ├── citations.yaml
    │   ├── sources.yaml
    │   ├── types.yaml    
    ├── _members                  
    ├── _posts   
    ├── .docker         # Docker-related files
    ├── blog            # Blog posts and related content
    ├── contact         # Contact information of the lab           
    ├── images          # Stores images used in the lab website
    ├── research        # List of lab publications
    ├── team            # Personal description for each lab member
    ├── _config.yaml    # Controls site properties, page defaults, site social media, and other links
    ├── index.md        # Controls the structure of the front page (sections and buttons)


## Materials needed
1. Images for lab website
2. Lab icon(s)
3. Overview of research interests (research overview)
4. Some example research paper (published?) and projects (ongoing?)
    - Brief introduction (abstract style?)
    - An image for the study?
5. Contact information (other than the email; probably an organization github repository?)
6. Personal description (and personal photo)

## Questions
1. paper tags, featuring papers (放3,5个可以对应research interest), paper links
2. 一些用于paper旁边的image（自己选择）
3. maybe tags based on three research interests? （可以用）
4. 首页的research interest可以配上图（直接放）
5. 原本首页的highlight或许就不要了？（暂时不需要）

加News section
加Tutorial界面（用来分享）