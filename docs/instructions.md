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

<p><details><summary>Merge the <b>challenge</b> branch into your <b>{{site.data.assignment.git-curr-branch}}</b> branch.</summary>

1. Go to **GitHub Desktop.**

- This adds a **Challenge 1** folder to your **Assets** folder.

</details>

<p><details><summary>Find the Challenge-1/Instructions video in the Assets folder. Watch the video to see how the game should work. Make notes about what you need to fix.</summary>

- Watch the video.
- Attempt to play the game.
- Make notes about the problems that you see in the game.
- Pick the first problem that you will work on.
    
</details>

<p><details><summary>After watching the video, try to fix the bugs. Use the hints if you get stuck.</summary>

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
    
   </details>
   
* The plane is looping

   <details>
    <summary>Hint</summary>
    
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
