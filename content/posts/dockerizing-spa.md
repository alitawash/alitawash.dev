+++
title = "Dockerizing a large-scale web application - A pre-Kubernetes guide"
tags = [
    "angular",
    "docker",
    "hasura",
    "PostgreSQL",
    "SPA",
    "golang",
    "development",
]
date = "2021-11-27"
toc = true
+++

## Introduction

I wrote this guide mainly for myself in order to avoid having to re-watch numerous courses in order to accomplish my goals of writing almost any type of application with my set of tools in an optimal pipeline (At the very least, I believe its), which includes an [Angular](https://angular.io/) application with Hasura that provides an instant GraphQL server using a `PostgreSQL` database and serverless actions written in [Golang](https://go.dev/). Additionally, the pipeline will comprise two environments test and production . Furthermore, it has a `CI/CD` pipeline for each components, which, when changed using the git command, immediately pushes changes to the git repository and, after testing, to the associated container.