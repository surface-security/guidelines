# Surface Security Guidelines

Surface Security is an open source security intelligence and automation platform, empowering Security Engineers around the world.

This project should provide a great base to allow teams and engineers to expand its capabilities to create a centralized inventory of all IT assets, applications, infrastructure and more. This repository contains general guidelines to contribute to the project, instructions on how we are working on it and other information on governance.

**If you are looking for specific instructions on how to contribute to one specific project this is not the correct place to look into.**

# Prioritising

We are currently working on ways to convert our roadmap into public. Until then, part of the workflow is invisible to most, but the way items get prioritised in `Surface-Security` is as follows:
1. All new issues assigned to the "Roadmap" project get pushed to backlog type of bucket;
1. Every quarter, the core team of the project will review that bucket and choose items that make sense to focus on the following quarter;
1. Bugs breaking a production build have priority for fixing;
1. Minor bugs should have priority over features in each quarter plan, but not during the cycle.

## Feature Requests and Bugs

Anyone is welcome to open new issues in the respective projects - and in fact we appreciate your help in reporting bugs, suggesting new features or raising concerns overall - but please be mindful when opening new tickets. This is still a volunteering initiative and it's easy to get lost in crazy amounts of tickets to process.

**Please fill in the requested templates, so it's easier for us to identify the source of the issue, the type of feature request, ask questions and so on.**


# Contributing

Anyone is welcome to contribute with code to all repositories. Some notes on how to do so:

- We promote [feature branch type of development](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches): clone the repository, create a new branch and open a pull request against your branch;
- Each project should have the specific instructions to build and run the project - no PR should be merged with failing tests so, please, try to have a working build beforing opening a PR; 
- Be descriptive in the pull request description, explaining what it fixes or adds, as well as the underlying issue that motivated the code change;
- New versions are published only when tags are created (and only admins have the rights to push tags);