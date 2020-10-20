# kottans-frontend
# Stage 0. Self-Study
## General
- [X] Git Basics
- [X] Linux CLI and Networking
- [ ] VCS (hello gitty), GitHub and Collaboration
## Front-End Basics
- [ ] Intro to HTML & CSS
- [ ] Responsive Web Design
- [ ] HTML & CSS Practice
- [ ] JavaScript Basics
- [ ] Document Object Model - practice
## Advanced Topics
- [ ] Building a Tiny JS World (pre-OOP) - practice
- [ ] Object oriented JS - practice
- [ ] OOP exercise - practice
- [ ] Offline Web Applications
- [ ] Memory pair game — real project!
- [ ] Website Performance Optimization
- [ ] Friends App - real project!

## Git Basics

#### What's new?

1. Find out that Git is **distributed version control system**
2. There are exists next three areas: **working directory** - where all current local files, than after `git add` they come to **staging area** and after `git commit` they appear at the **repo**.
3. Good advices: always make `git status` command after any other commands and when creating some new feature always make `git branch --name--` new branch.
4. **.gitignore** file is useful when you need to prevent some files(e.g images, logs etc.) from adding them to the repo.
5. After use `git log` it's very convinient to use next commands for navigation in **CMD**:
  - **scroll down**
  - **d**-move half page screen or **f**-move whole page screen
  - **scroll up**
  - **u**-move half page screen or **b**-move whole page screen
6. Learned different types of log viewing by using next commands `git log --oneline`, `git log --stat`, `git log -p`.
7. Also `git show` useful command for a single commit.
8. `git diff` - shows changes in a local files before commiting.
9. For making undo **after** last incorrect commit make `git commit --amend`.
10. `git reset` is good for local repo - erase commit/ `git revert` is nice for remote repo - make a copy of commit with opposite state.

#### What's surprised?

1. Definitely amount of different approaches to move commits between branches.

#### What's intend to use in the future?

1. All mentioned commands ;)

[Lesson screenshots](https://github.com/AntonGluschuk/kottans-frontend/tree/main/git_basics)

## Linux CLI, and HTTP

#### What's new?

1. Found out that `mv` command have opportunity to Rename and Move Files/Directories.
2. First time worked with change file permission command: `chmod` + `ugo-rwx` + `<filename>` where **u** stands for user, **g** - group of users, **o** - other/world and **r** means - read, **w** - write, **x** - execute.
3. Also opened for myself different wildcards like `*` - stands for all files and `?` - means one character.
4. First [article](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177) filled in knowledge about request verbs: **GET** - fetch an existing resource, **POST** - create a new resource, **PUT** - update an existing resource, **DELETE** - delete existing resource - all of them are most popular requests.
5. In second [article](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-2--net-31155) I got my feet wet of understanding:

  - **Authentication** - user doing request; server respond with a `401 (Unauthorized)` and provides info about authorization through the `WWW-Authenticate` header; than user send new request with authorization data including ` Authorization` header.
  - **HTTP Caching** - optimized process of obtaining resources from the web cache bypassing the request to the server, cache helps save time, cost and bandwidth, as well as provide an improved experience on the web.
  - **Identification** - mandatory option of the servers to find out info about the user who tried to establish connection, mostly it's doing through the cookies.

#### What's surprised?

Surprized the amount of headers and different status codes and internal structure of the HTTP Protocol.

#### What's intend to use in the future?

For sure I will try to do requests by using some public API to learn everything on a practice about different server responses.

[Lesson screenshots](https://github.com/AntonGluschuk/kottans-frontend/tree/main/task_linux_cli)
