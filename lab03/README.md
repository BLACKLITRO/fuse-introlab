## Lab three - Create a GIT repository for your code

In this lab we are going to sync our code with a new GIT repo. We are refering/using a Gogs Git server deployed into Openshift (In this [link](https://github.com/OpenShiftDemos/gogs-openshift-docker) you can see how to do that)
You are free to use any other Git public/private repo like Github, Gitlab, etc.

> We will be referencing this Git server url as: $GIT_URL
  
> And the Git user will be: user1

## Create a repository 
1. Go to the $GIT_URL and then create a new account named "user1" password "openshift".

![1-git.png](./img/1-git.png)

2. Now login with that account.

![2-git.png](./img/2-git.png)

3. Then create a new repo named: "myfuselab"

![3-git.png](./img/3-git.png)

## Sync your local code with your new Git repo
1. In CodeReady Studio (CRS), go to "*Window > Perspective > Show Perspective > Other ...*"

![4-git.png](./img/4-git.png)

2. Select the Git perspective

![5-git.png](./img/5-git.png)


3. Create new Git Repo in CodeReady Studio...
Go to the icon that says Create new Git repo and click on it.

![6-git.png](./img/6-git.png)

4. Fill all with your Git repo info then click Next...

![7-git.png](./img/7-git.png)

5. In the next screen do not select nothing, just click Next...

![8-git.png](./img/8-git.png)

6. Then in the final screen select some local directory from your disk. Then click Finish.

![9-git.png](./img/9-git.png)

7. Change the perspective to the "Fuse Integration" perspective. Then right click on your project and then select "**Team > Share project ...**"

![10-git.png](./img/10-git.png)

8. Now select Git, click Next. Then from the Repository list select the Git repository that you recently added to your workspace.

![11-git.png](./img/11-git.png)

If all was ok, now you just linked your local project with the remote repo in the Git server. Next step, commit and push your code.

## Commit and push your code to remote Git repo.

1. In Git, first you have to add any new file to the local git repo index so that file can be versioned and be part of the repo. To do so, right click on your project, then "**Team > Add to index ...**"

![12-git.png](./img/12-git.png)


2. Now all yorur files are part of your local git repo and we can do a Commit and Push of our code/changes to the remote git repo. Right click on your project, then "**Team > Commit ...**"

![13-git.png](./img/13-git.png)

3. Put some comment and then click on Commit / Push button. Select **master** branch and put your user credentials when asked.

4. If all was ok, your code now is on the remote git repo.

![14-git.png](./img/14-git.png)



























