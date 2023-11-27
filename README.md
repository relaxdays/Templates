# Relaxdays.Templates

## Overview

This repository contains templates for relaxdays projects, e.g. reusable github workflows.

## Structure

Reusable github workflows are located under `.github/workflows`. Language specific workflows are prefixed with the
language name, e.g. `dotnet-test.yml` for a dotnet test workflow.

This is a restriction imposed by github workflows semantics, as documented
[here](https://docs.github.com/en/actions/using-workflows/reusing-workflows#creating-a-reusable-workflow):

> As with other workflow files, you locate reusable workflows in the `.github/workflows` directory of a repository.
> Subdirectories of the workflows directory are not supported.

For that reason, to make it easier to differentiate between workflows meant to be reused and workflows internal to
this repository, the latter are prefixed with `internal-`.
