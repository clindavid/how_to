# Shiny Server Maintenance Guide

This repository contains a collection of procedures, troubleshooting guides, and operational notes required for maintaining the Shiny Server infrastructure that hosts our dashboards.

Each document focuses on a specific administrative task and is named accordingly.

## Contents

### 1. Git Token Setup and Refreshing (`git token set up and refreshing.qmd`)

Provides step-by-step instructions for:

* Creating and configuring a GitHub Personal Access Token (PAT)
* Authenticating Git operations on the server
* Refreshing or replacing expired tokens
* Verifying token functionality

### 2. Lock R Version (`Lock R version.qmd`)

Describes how to:

* Install a specific R version on the server
* Prevent automatic upgrades through package managers
* Maintain version consistency across deployments
* Verify the active R version

### 3. Disable Symlinks (`Disable symlinks.qmd`)

Explains how to:

* Disable symbolic links within `renv` package libraries
* Configure `renv` to use package copies instead of symlinks
* Resolve common issues related to symlinked packages in deployment environments
