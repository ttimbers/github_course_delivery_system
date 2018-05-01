## Activity overview

Now that we're set up to use Git, let's walk through a workflow very similar to what the students would do (and learn a little Git along the way!)

1. Get your own copy of the example homework folder (Github repository)
2. "clone"" that copy to a place you can edit the files (e.g.,[ubc.syzygy.ca](https://ubc.syzygy.ca/) or your own computer if you have already have Git installed there)
3. Edit and save the changes to the files
4. Use Git to log the changes ("add" and "commit")
5. Send the logged Git changes to Github ("push") to submit the work

## 1. Get your own copy

Go to the URL below and click on the "Fork" button (top right-hand corner)

https://github.com/UBC-MDS/eg_hwk

## 2. "clone"" that copy to a place you can edit the files

- Click on the "Clone or download" (green button) of the new website you were directed to. Copy the URL that pops up.

- Go back to the "Terminal" on [ubc.syzygy.ca](https://ubc.syzygy.ca/) and type the following (replace URL with the URL you just copied):
  ```
  git clone URL
  ```
- using "Terminal" navigate into that directory by typing `cd eg_hwk`

## 3. Edit and save the changes to the files

- Click on the "Home" [ubc.syzygy.ca](https://ubc.syzygy.ca/) tab in your browser and use the file navigator to find `homework.md` in the `eg_hwk` directory/folder
- Follow the instructions to answer the homework questions
- Save the changes (File -> Save)

## 4. Use Git to log the changes 

- Go back to the "Terminal" on [ubc.syzygy.ca](https://ubc.syzygy.ca/) 
- Ask Git what files were changed by typing: `git status`
- log those changes to git by typing the following two lines into terminal:
  ```
  git add homework.md
  git commit -m "first attempt at homework questions"
  ```

## 5. Send the logged Git changes to Github ("push") to submit the work

- In the "Terminal" on [ubc.syzygy.ca](https://ubc.syzygy.ca/) type (*note - you will be asked to enter your Github username and password here*):
  ```
  git push
  ```
- Go back to your copy of the homework on [Github.com](https://github.com/) and check to see that you were successful in submitting this homework.
