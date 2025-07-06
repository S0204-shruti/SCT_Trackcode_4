# SCT_Trackcode_4

Key Features:
Task Input:
An input box (#inputBx) accepts user tasks. Tasks are added by pressing the "Enter" key.

Dynamic Task Addition:
On pressing Enter, the task is dynamically added to an unordered list (#list) as a <li> element.

Marking Tasks as Done:
Clicking a task toggles a .done class (to be styled in CSS), indicating it is completed.

Deleting Tasks:
Each task includes an empty <i> tag, which when clicked, removes the task from the list.

Clean UI Structure:
The structure is organized in a container and box div, and the layout is separated from logic using an external CSS file (style.css).

💡 What I Learned:
How to use DOM manipulation (document.querySelector, createElement, appendChild) to dynamically update content.

How to handle keyboard events with addEventListener("keyup", function...).

How to attach event listeners to elements that are dynamically created.

Importance of clean HTML structure and interactive UI behavior.
