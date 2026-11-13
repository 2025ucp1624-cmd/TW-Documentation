
# GitHub - Hosting and Collaboration

## What I Learned

GitHub is an online platform where we can store and share projects that use Git. It makes collaboration easier because developers can upload their code, work on different features, and review each other's changes.

I learned that Git works locally on our computer, whereas GitHub provides a remote place to store our repositories.

## Creating and Uploading a Repository

To upload a local project to GitHub, we first create a new repository on GitHub. Then we connect our local Git repository to it.

Some commands used in this process are:

```bash
git branch -M main
git remote add origin REPOSITORY_URL
git push -u origin main
```

Here:

 `git branch -M main` renames the current branch to `main`.
 `git remote add origin` connects our local repository to GitHub.
 `git push` uploads our commits to the remote repository.

## Important Concepts


 Repository | A place where project files and their history are stored. |
 Remote | A connection to a repository hosted online. |
 Push | Uploads local commits to the remote repository. |
 Pull | Downloads and integrates changes from the remote repository. |
 Fetch | Downloads remote updates without integrating them into the current branch. |
 Clone | Creates a local copy of an existing remote repository. |
 Branch | Allows us to work on a feature separately from the main code. |
 Pull Request | Allows us to propose changes and request their review before merging. |
 Merge | Combines changes from different branches. |
 Merge Conflict | Happens when Git cannot automatically combine certain changes. |

## Branches and Pull Requests

One useful feature of GitHub is that we don't always have to make changes directly to the main branch.

For example, if I want to add a new feature, I can create a separate branch, make changes there, and push that branch to GitHub. After that, I can create a pull request to ask for the changes to be reviewed and merged into the main branch.

This makes it easier to work on projects with other developers.

## Practical Uses

- Storing projects online.
- Sharing code with other developers.
- Working on different features using branches.
- Reviewing code through pull requests.
- Tracking bugs and tasks using Issues.
- Maintaining project history.

## My Understanding

I understood that GitHub is more than just a place to upload code. It provides tools that help developers work together and manage projects.

I also learned the basic process of publishing a project: create a repository, connect it to the local Git repository, and push the commits. Branches and pull requests make it possible to develop and review features without directly disturbing the main project.
