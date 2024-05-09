# OMES Repository Standards

<img src="https://branding.ok.gov/wp-content/uploads/2020/02/OK_Logo_Horizontal_FullColour_Pos_RGB-768x212.png" height="150px" alt="OMES" />

_These are our internal-facing guidelines, at the time we have no plans for how to handle open code._

This project contains checklists, templates and other resources to include with your repository. Whether you're starting a new project or improving an existing one, please include any or all of the elements suggested below as appropriate to your repo.

## Get the Basics Right
>"There are two hard things in computer science: cache invalidation, naming things, and off-by-one errors."  
> – Leon Bambrick

- [ ] Give the repo a name in the following fashion. 
  - Monorepo - `Agency.Product`  
    _Examples_
    - OMES.AppName
  - Microrepo - `Agency.Product.Function`  
    _Examples_
    - OMES.AppName.Service
    - OMES.AppName.Common
    - OMES.AppName.Desktop
    - OMES.AppName.Website

- [ ] Give your repo **a description** and **some topics** - you can set these at the right side of the web interface, next to the file listings. The description should cover the purpose and scope of the project. The tags should include the technologies used and the features of the project. For example you could have tags: `c#` `node` `sql` `2fa` `postgres` ect.

- [ ] Use the [basic README template](basic-readme-template.md) as a starting point for your repository.

## More README Resources

You may find these resources useful for structuring your project's README file (edit and add your favorites!)

- https://github.com/noffle/art-of-readme
- https://gist.github.com/PurpleBooth/109311bb0361f32d87a2
- https://betta.io/blog/2017/02/07/developer-experience-github-readmes
