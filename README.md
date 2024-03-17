# Mono Repo Checkout 
This repo is a test of a mono-repo workflow where one repo (this one) is used to pull and test the contents of another repo

For example, this repo could be a Unity project, and the mono-repo could hold unity assets (or even assets for multiple engines) that aren't tied to any one project.

## Theory
Through the sparse checkout feature we should be able to set up multiple submodules, with each submodule pointing to specific path in the mono-repo instead of pulling in the entire thing. Allowing for people to edit files without needing to pull the ENTIRE thing. 