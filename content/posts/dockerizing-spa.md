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

I wrote this guide mainly for myself in order to avoid having to re-watch numerous courses in order to accomplish my goals of writing almost any type of application with my set of tools in an optimal pipeline, which includes an Angular application with Hasura that provides an instant GraphQL server using a PostgreSQL database and serverless actions written in Golang. Additionally, the pipeline will comprise two environments test and production . Furthermore, it has a CI/CD pipeline for each components, which, when changed using the git command, immediately pushes changes to the git repository and, after testing, to the associated container.