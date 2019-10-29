---
layout: tabbed-assignment
---

<!-- Don't edit links here, change them in _data/assignment.yml instead. -->

[lesson]: <{{site.data.assignment.lesson}}>
[slides]: <{{site.data.assignment.slides}}>
[template]: <{{site.data.assignment.template}}>

# Instructions

{% include time-estimate.html %}

<p>
<details>
<summary>Launch GitHub Desktop and make sure that your local copy of the {{site.data.assignment.starter-code-repo}} repository is up to date.</summary>

- Make sure that your **{{site.data.assignment.starter-code-repo}}** repository is selected.
- Do a **fetch** to make sure your local copy of the code is up to date, if you have done work on the GitHub site or at home between classes you will be prompted to do a **pull** to incorporate your changes.
- Make sure that you are on the **{{site.data.assignment.get-prev-branch}}** branch.

</details>

<p><details><summary>Create and publish a {{site.data.assignment.git-curr-branch}} branch.</summary>
    
- When creating the branch, select the option to bring your changes forward from the **{{site.data.assignment.get-prev-branch}}** branch.
- If you forget to do this your work on the **{{site.data.assignment.get-prev-branch}}** branch (and all of the branches before it) will vanish. To recover, delete the **{{site.data.assignment.git-curr-branch}}** and recreate it.

</details>

<p><details><summary>Merge the <b>origin/challenge</b> branch into your <b>{{site.data.assignment.git-curr-branch}}</b> branch.</summary>

In **GitHub Desktop:**

1. Make sure your **step-5** branch is selected.
1. Click on the down-arrow next to **step-5**.
1. At the bottom of the panel, click on the **Choose a branch to merge into {{site.data.assignment.git-curr-branch}}** button
1. Under **Other branches** choose **origin/challenge**.
1. Click on the **Merge origin/challenge into step-5** button.

This mill add a **Challenge 1** folder to your **Assets** folder. The **Challenge 1** folder holds the assets you will use for this assignment. You can also use your work on Prototype 1 for reference.

</details>

<p><details><summary>In the <b>Challenge 1</b> folder, find the <b>Challenge 1</b> scene file and open it (double-click on it) and explore the game.</summary>

- Look over the Hierarchy and the assets in the **Challenge 1** folder.
- Check out the **Game view**.
- Try to play the game.
    
</details>

<p><details><summary>In the Challenge-1/Instructions folder find the **Challenge 1 - Outcome** video. Study the video and the game to see what you will need to fix.</summary>

- Watch the video.
- Make notes about the problems that you see in the game.
- Pick the first problem that you will work on.
    
</details>

<p><details><summary>After watching the video, try to fix the bugs. Use the hints below if you get stuck.</summary>

If you're stuck, use the hints below:

* The plane is going backward.

   <details>
    <summary>Hint</summary>
    
    Make the plane go forward.
    
    ```Vector3.back``` makes an object move backwards, use ```Vector3.forward``` to make it go forwards.
    
   </details>

* The plane is going too fast

   <details>
    <summary>Hint</summary>
    
    Slow the plane down to a managable speed.
    
    If you multiply a value by ```Time.deltaTime```, it will change it from 1x/frame to 1x/second.
    
   </details>
   
* The plane is looping

   <details>
    <summary>Hint</summary>
    
    Make the plane climb or dive only if the user presses the up/down arrows
    
    In **PlayerControllerX.cs**, in ```Update()```, the ```verticalInput``` value is assigned, but it’s never actually used in the ```Rotate()``` call.
    
   </details>

* The camera is in front of the plane

   <details>
    <summary>Hint</summary>
    
   </details>

* The camera is not following the plane

   <details>
    <summary>Hint</summary>
    
   </details>

</details>

<p><details><summary>Submit your work.</summary>

When you're done for the day, go to the submission tab, check the instructions, and submit.

</details>
