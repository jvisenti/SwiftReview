# SwiftReview

A sandox repo for Swift code reviews for the Spring '16 Mobile Computing class. Code submitted via a Pull Request will be treated as a real code review. The goal is to introduce students to both Git and the code review process.

**NOTE:** Code for assignments will *not* be reviewed.

## How it Works

1. Fork this repository (button in the top right of the screen while logged into GitHub).
2. Clone your fork on your machine:
  ```
  git clone https://github.com/<your_github_username>/SwiftReview.git
  cd SwiftReview
  ```
  
3. Create a new branch:
  ```
  git branch <your_branch_name>
  git checkout <your_branch_name>
  ```
  
  
4. Add any files you want to be code reviewed to the local SwiftReview directory, and then commit:
  ```
  git add -A
  git commit -m "<your_commit_message>"
  ```
  
5. Push your branch up to the remote:
  ```
  git push --set-upstream origin <your_branch_name>
  ```
  You will now see your branch in the branches dropdown on the GitHub page for your fork.
  
6. Go to the GitHub page for your fork (`https://github.com/<your_github_username>/SwiftReview`), and click the `New Pull Request` button.
  
7. Select your branch from the right side dropdown menu. You should see a diff appear below showing the changes you made on your branch. Provide a relevant title and description, and then click `Create Pull Request`.
  
8. Wait for your code to be reviewed. Leave a comment on your pull request tagging `@jvisenti` for quicker review.
