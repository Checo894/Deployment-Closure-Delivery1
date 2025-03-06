# Deployment-Closure-Delivery1

## MADE BY:

- Sergio E. Gutiérrez T.
- 

## Asigment description:

Use Git and Github to implement the following pipeline denoting a version management and collaborative work model.

## Objective:

Know and learn the computer tools Git and Github for version management and collaborative work during the software life cycle

## Pipeline:

![image](https://github.com/user-attachments/assets/6d1072d5-206b-4664-9075-f5b17a32bd7f)

# Commit NEW *2* from local

For this, we ran the following commands:

`git log --oneline` - Visualize Commit's History

    628b360 (HEAD -> branchParaCommit5, origin/branchParaCommit5) Commit5
    741c553 (origin/main, origin/HEAD, main) Commit4
    cc913c7 Commit3
    ad5c37d Commit2
    cd00a46 Commit1
    4a60c1e Initial commit

`git checkout ad5c37d` - With the commit2 id, we go back to that state in the history

`git branch` - Here we verify we are in a detached head branch at Commit2

    * (HEAD detached at ad5c37d)
      branchParaCommit5
      main

After this, we modify the Commit2 README.md to add all of these comments, and finally do a new commit (Commit7) to push and merge the changes into main.

# FINAL RESULT

![image](https://github.com/user-attachments/assets/bf38c00a-f414-4c49-8352-a36577311ed4)
