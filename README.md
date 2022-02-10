# Assignment Repository <a href='https://bogaziciai.com//'><img src='media/bogaziciai-logo-sq.png' align="right" height="139" /></a>

This repository will be used to upload and manage assignments
in our lectures.

Each student will work on a branch for each assignment. The assignments
will be commited under the folders named with students' name. After commiting
assignment, a Pull-Request will be sent an a review will be asked.

As the reviewers approve the PR, the assignments could be merged to the
main repository.

### How to submit assignment

#### Clone repository

After you install `Github Desktop`, clone repository using `Add`
button there.


<img src="/media/1-clone-repository.gif">

If you are on command line:

`git clone https://github.com/bogaziciai/assignment.git`

#### Create new branch

Create a new branch for each submit, name your branch as
`task{number}-{your_name}`. Replace values in brackets
for your task number and name. Brackets are the convention
to indicate variable, don't use them in your branch.


<img src="/media/2-create-branch.gif">

or

```
git checkout -b task{number}-{your_name}
```

#### Submit your assignment

1 - Add `-{your_name}` to your solution files


<img src="/media/3-1-submit-assignment-naming.gif">

2 - Commit, push to origin, and send a `Pull Request`.
Try to be simple in your messages, you don't need to add any
details at all.

<img src="/media/3-2-submit-assignment-commit-push-pr.gif">

or

```
git checkout -b task{number}-{your_name}
git add .
git commit -m "{your message}"
git push
# go Desktop app or website to create PR o
```

3 - Add us to reviewers @bkavlak & @isikz

<img src="/media/3-3-submit-assignment-add-reviewer.gif">

#### Check reviews `ReviewNB` application.

Since we'll mostly use `Jupyter Notebooks`, we will add our
comments on `ReviewNB`. You can find links to comments in your PR.

<img src="/media/4-see-reviews.gif">