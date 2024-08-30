# Learn-to-learn

This is the entry-point for the Barlow Robotics (FRC team 4572) software
learning curriculum. Completion of the required portions of this curriculum
are necessary for the 2025 FRC Robotics year.

The goal of this module is to familiarize you with the learning framework
itself, as well to ensure you have all the tools necessary to get started
on the additional modules.

## Background

This is a new process we are introducing for 2024 FRC year to help provide a
stronger foundation for those contributing to the software codebase.

These modules take a competency-based approach that emphasizes:
- Defining what you need to learn and why.
- Guiding you to resources to help learn the materials.
- Providing a means to demonstrate a basic level of competency.

Note that these learning resources are under active development and are only
a best effort starting point. This means that the provided resources may be incomplete,
and the suggested demonstrations of competency may not be comprehensive.
You should always revisit the objects and make sure you feel comfortable with
the concepts before moving on to another module. 

The list of additional learning modules can be found in the
[learning_index](learning_index.md) in this repository. You should bookmark that
page so you can refer back to it when looking for additional modules. Each
module will follow a similar structure that should become familiar as you work
through the process. Good luck!

## Assumptions & prerequisites
- This module only assumes you have access to a computer with the necessary
  permissions to install software.

## Objectives and motivation
- Learn how to find and work through the other learning modules.
  - This is how you will demonstrate your proficiency in the skills necessary to
    contribute to the 2025 Software codebase. 
- Establish a working environment on your computer that includes the VS Code and
  WPILib tooling.
  - These are the standard tools we use to develop all team software. Using the
    standard tools for the team makes it easier to collaborate with and support
    all team members.
- Learn the basics of git, including cloning a repository, making edits, and
  submiting pull requests.
  - These are necessary parts of our software development process. Our learning
    modules use this same workflow for consistency and to familiarize you with
    the process.

## Demonstration of competency

To complete this module you should:
- Install WPILib & VS Code on your laptop.
- Clone this repository.
- Create a branch, and make an edit to the file `demonstration.md`.
- Submit a pull-request to the repoistory including your changes.

# Resources

Note that many of the linked resources go into deeper technical detail than is
necessary for this module. Don't try reading these all end-to-end or you will
very likely get overwhelmed. These are mostly here so that you know the material
is there if/when you need to go looking for it.

Try following along with the steps from `More detailed steps` section and the
video walkthrough (coming soon), and then refer to the additional links as necessary.

## Barlow-developed resources
- Video Walkthrough
  - TODO: We should record a short video walkthrough of going through just the minimal relevant steps.

## Installing WPILib & VSCode
- [WPILib documentation](https://docs.wpilib.org/en/stable/)
- [WPILib installation](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html)

## VS Code details
- [VS Code interface](https://code.visualstudio.com/docs/getstarted/userinterface)
- [VS Code introduction](https://code.visualstudio.com/docs/introvideos/basics)

## Working with Git
- [What is version control](https://git-scm.com/video/what-is-version-control)
- [Github Desktop](https://github.com/apps/desktop)

# More detailed steps

## Installing WPILib & VS Code

IMPORTANT NOTES: 
- Even though VS Code is a standalone application that you can install
separately we always use the VS Code that is bundled with the WPILib installer.
This is because it comes with important extensions for deploying code and
running simulations. Even though we're not doing those activities yet, it's best
to just be consistent.
- These instructions currently have you install the 2024 WPILib. Sometime before
the competition kicks off, you will also need to install the 2025 WPILib
instead.

The [WPILib documentation](https://docs.wpilib.org/en/stable/) is very
comprehensive. We'll frequently refer back to it as we expand the topics covered
in future modules. However, for now you can jump straight to the
[installation guide](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html)

When following the installation guide, make sure you use the link to the
[2024.3.2 release](https://github.com/wpilibsuite/allwpilib/releases/tag/v2024.3.2)
to get the most recent installation materials.

Follow the installation guide and ensure that when you are done you can launch
VS Code from the shortcut on your desktop. If you are having issues completing
the installation or finding the VS Code application, consult a mentor or team
member.

If you've never used VS Code before, you may find it helpful to review some of this content:
- [VS Code interface](https://code.visualstudio.com/docs/getstarted/userinterface)
- [VS Code introduction](https://code.visualstudio.com/docs/introvideos/basics)

## Cloning this repository

Once you have VS Code installed and can run it, the next step is to clone this
repository. Cloning is the process of downloading a repository from github to
your local computer.

This short video about version control is a helpful way of introducing yourself
to some of the concepts that are going to come up frequently:
- [What is version control](https://git-scm.com/video/what-is-version-control)

When it comes to actually working with git there are three main options:
- [Github Desktop](https://github.com/apps/desktop) is a standalone application
  (this is recommended)
- [Git in VS Code](https://code.visualstudio.com/docs/sourcecontrol/intro-to-git) lets you
  work with git directly from within VS Code, but the UI is less user-friendly.
- [The git command-line](https://git-scm.com/downloads) lets you use git from
  the terminal. This can be the most powerful, but the hardest to get started.

You are free to follow the guides on working with git from within VS Code or the
command-line, but if you're new to git we highly recommend simply installing the
github desktop the [github desktop](https://github.com/apps/desktop)
application.

If you do not have a github account, you will need to create one to log into
github.
  - TODO: Are there Barlow specific details students need to follow when
    creating an account?
  - Once you have created an account, ask one of the mentors to add you to the
    `https://github.com/Barlow-Robotics/` repository.

If the git tools are installed and you are logged into your github account, when
you launch github desktop, you should see `Barlow-Robotics` under `your
repositories`. Search for the `learn-to-learn` repository, select it, and then
click the `Clone` button. You will be prompted to choose a local path to save
the repository.

Once you are done, go back to VS Code, and open the folder you just created. You
should be able to see this file in the VS Code file explorer.

## Making changes

Before making any changes, you should create a new branch.

Branches let you keep track of just the work you are doing relative to other
members of the team working in the same repository. By developing in your own
branch you can avoid running into conflicts with other developers until you are
ready to merge.

See: [making changes in a branch](https://docs.github.com/en/desktop/making-changes-in-a-branch/managing-branches-in-github-desktop)

Start by making a new branch.  It's helpful to name your branch using your name
and a short description so team-members know who is doing the work. For example:
`jleibs/update-learning-module-links`

Once you've create a branch, you can go back to VS Code. Open, and modify the
file: `demonstration.md`. You can make some changes and then save your edits.

When you return to github desktop you should see `demonstration.md` in the list
of changed files. Select the checkbox next to the file, and then click the
`Commit` button. You will now have an option to publish your branch to github
using the `Publish Branch` option. Once your branch is published, it can be seen
and downloaded by other members of the team on github.

Finally, you can now create a pull request. Click the `Preview pull request`,
which will summarize the changes you've made, and finally click `Create pull
request`. This will take you to a github page that allows you to create a pull
request back to the main branch. A pull request still won't make any changes to
the main branch of the repository. However, if notifies other team members of
the fact that this code is available and ready to be considered for inclusion.
The pull request UI will let you and others review the changes to make sure you
are only changing the things you intend to and not accidentally reverting or
removing other changes unintentionally.

## Next steps

One of the mentors will review the fact that you've created a pull-request and
merge your change into the main repository.

If you want to continue practicing the git tools you can make additional changes
and continue to sync them into your branch. We will cover more advanced git
topics such as merging and resolving conflicts in another learning module.

When you're ready, you can go back to [Other learning modules](learning_index.md)
and follow the next learning module.