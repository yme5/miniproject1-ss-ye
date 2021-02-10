# GitFlow

## What is Gitflow?
GitFlow is a model for how to conduct pranching when creating a product. It is designed so teams can develop different features simultaneously, while keeping the code base organized. 

## How does it work?
The user begins by creating a 5+ branches;
1.  The Main branch is the branch inteneded for released code only. This is the product the customer sees 
2.  The Develop branch is where features are pulled from. 
3.  The Feature branch is where feaures are made
4.  The Release bracnh where the features are tested in unison. 
5.  The Hotfixes branch is where the emergency bugs are fixed ONLY. Nonemergency bugs are fixed in the release branch. 

A product in the GitFlow workflow is only worked on in the Develop branch. When a product is ready for deployment to customers, it pushed to the Main branch. This version of the product is tested to be bug free, and has all of its features documented in release notes. When it comes time for a new feature, for example; a new interface, the developer will pull the code from the Develop branch into a new branch named after the feature, in this case called New Interface. Here the developer will create functionality, fix bugs, test and commit until they feel the feature is ready. Then they will merge it back into the Develop branch, where other groups can test the feature and its functionality, as well as create more features using the newley added feature. In this example, after the code is added back into Develop, someone can come and pull the code into a new featuer called New Button. When enough features are added, they are all pulled into the release branch, where extensive testing is done to eliminate any bugs. Then, the release branch is merged with the main branch, and the product is off to shipment. 

## Why use it?

GitFlow is best when it is applied to products that are continuosuly improving, and it is genreally good practice to follow this workflow to keep confusion down and productivity high. It is up to the team to maintain the workflow and keep all the branches organized, and in doing so they ensure their overall success. 


![image](Images/gitFlow.png)
