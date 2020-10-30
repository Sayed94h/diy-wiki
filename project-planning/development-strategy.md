# Diy Wiki Project

Practicing more about server side programming with Node JS and Express JS

## 1. Setup

1. fork this repo
1. clone this repo
1. turn on GitHub page
1. install dependencies
1. play with demo to understand the tasks

## 1. Write-to-files

**As a user I would like to be able to write, edit and add to a file in the database**

This part is done in a branch called `write-to-file`
This branch is merged to the master after is was completed

#### tasks

- Create a new page
- Change a page content
- Write the changes to a markdown file
- If there is no problem, send ok to clients otherwise send an error

## 1. get-all-pages

**As a user I would like to be able to find all file names inside a directory in the database**

This part is done in a branch called `get-all-pages`
This branch is merged to the master after is was completed

#### tasks

- look inside a directory for file names
- check if file names have any extension
- remove the file name extension
- store the file name without extension in an array
- send the array as a json file with the status "ok"

## 1. get-all-tags

**As a user I would like to be able to find all tags inside files in the database**

This part is done in a branch called `get-all-tags`
This branch is merged to the master after is was completed

#### tasks

- look inside a directory for file names
- read each file and check if it contents any word with "#" at the beginning
- store all words with "#" in an array
- send the array as a json file with the status "ok"

## 1. tag-in-files

**As a user I would like to be able to find all tags inside files in the database**

This part is done in a branch called `tag-in-files`
This branch is merged to the master after is was completed

#### tasks

- look inside a directory for file names
- read each file and check if it contents any word with "#" at the beginning
- store all words with "#" in an array
- store the the file name which contains a specific tag in another array
- remove the file name extension
- send the array as a json file with the status "ok"
- remove duplicates of tags from the route "/api/tags/all"
