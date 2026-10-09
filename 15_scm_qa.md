# 5. SCM and QA Strategies

## 5.1 Source Control Management (SCM)

We will use Git and GitHub to manage the code for a team of 4 members.

### Branching Strategy
We used a simple strategy to preserve the core code, divided into three sections.



### - `main`
The concept:

This is the final and complete version of the Makasib platform, which will be presented to the evaluators and observers on the day of the presentation.

Laws:
1. Direct uploading is not alawed.
2. The code can only be entered through integration and has been previously tested.




### - `development`
The concept: It is a draft compilation for the four members, so that any member who finishes a part puts it in the development.

Laws:
1. Any feature that has been completed in its own branch is integrated into development.
2. After completing the testing of the version located in development, We transfer updates to the main page .




###  - `feature/*`
  The concept: A separate branch is created when starting work on a part of the project, so as not to disrupt other work.


  
  Laws :
 1. When we finish working on a feature in the feature section, it is integrated into development.
2.  Once merged, it is removed from the feature list.

  
### - `hotfix/*`
The concept:
 An exceptional branch we use only in case of an emergency.


