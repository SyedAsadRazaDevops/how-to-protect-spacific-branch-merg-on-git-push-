# **Managing a branch protection rule**
you can create a branch protection rule to enforce certain workflows for one or more branches, such as requiring an approving review or passing status checks for all pull requests merged into the protected branch.

**NOTE**
>Protected branches are available in public repositories with GitHub Free and GitHub Free for organizations, and in public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server.

# 1-About branch protection
You can create a branch protection rule in a repository for a specific branch, all branches, or any branch

# 2-Creating a branch protection
On main page of the **repository**, Under your repo. click **Settings**. 
In section of the sidebar, click **Branches**.
Next to "Branch protection rules", click **Add rule**.

![chrome_aRWYroM58K](https://user-images.githubusercontent.com/71556060/176152455-5d77e9b3-b018-4a1b-824b-2490b5e462e2.png)

Under "Branch name pattern", type the branch name or pattern you want to protect
Under "Protect matching branches", select Require a pull request before merging.

![PR-reviews-required-updated](https://user-images.githubusercontent.com/71556060/176152713-8ef66c27-6d59-4329-842d-3874f06d4af9.png)

Optionally, to require approvals before a pull request can be merged, select Require approvals, click the Required number of approvals before merging drop-down menu, then select the number of approving reviews you would like to require on the branch. 

![number-of-required-review-approvals-updated](https://user-images.githubusercontent.com/71556060/176152840-751516eb-a9e7-4dbe-b899-b13c17a3dc9f.png)

Optionally, to dismiss a pull request approval review when a code-modifying commit is pushed to the branch, select Dismiss stale pull request approvals when new commits are pushed. 

![PR-reviews-required-dismiss-stale](https://user-images.githubusercontent.com/71556060/176152939-487dbc5d-bc82-43b7-9c3d-5f976a1dffec.png)

Optionally, to require review from a code owner when the pull request affects code that has a designated owner, select Require review from Code Owners.

Optionally, to require review from a code owner when the pull request affects code that has a designated owner, select Require review from Code Owners.

Optionally, to allow specific actors to push code to the branch without creating pull requests when they're required, select **Rules applied to everyone including administrators**. Then Click on **Allow force pushes**,ans select **Specify who can force push**.
NOW, search for and select the actors who should be allowed to skip creating a pull request. 

![chrome_yEyeISXBoF](https://user-images.githubusercontent.com/71556060/176154710-206be65a-e561-4715-805d-ddf20e93541f.png)

and click to **Create**.


Send the commit on main protection branch it will pending.

![chrome_tl9dIqqHNQ](https://user-images.githubusercontent.com/71556060/176155529-1d2e395d-72f3-4115-af31-7b67dce82558.png)

on the admin user site recived the pull request on commit the code

![image](https://user-images.githubusercontent.com/71556060/176379273-95e182d3-2f12-4e62-99c1-ce624d372390.png)

now view the changes and approve it.

![image (1)](https://user-images.githubusercontent.com/71556060/176379505-941c0b7e-c424-460f-bdfd-6bd254a6517a.png)

now you can merge the request, on the specific branch ,i used the main.

![image (2)](https://user-images.githubusercontent.com/71556060/176380029-f21558a3-3ecc-428e-b7a3-7a6da0c6b496.png)

now its all done , noew you have the option to delete the branch which is tempraraliy created  ranch formate like (username_patch_no.#) 

![image (3)](https://user-images.githubusercontent.com/71556060/176380127-5c08a186-f38a-40ec-8d28-841f2c5d4006.png)


[LINK]: https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/managing-a-branch-protection-rule


