# FOLD Developer Interview Project

* This to-do list application is built upon the template at https://github.com/tastejs/todomvc/tree/gh-pages/examples/angularjs to fulfill the requirements for the project round of the Fool's FOLD Developer interview cycle.

## Setup
* To get this application running on your device, please clone the repository (or download it as a zip) and simply open the index.html file in the root folder!

## Features
* This to-do list application gives you the ability to search through the various tasks you have added to your list.
* Upon adding a new task, it is given the priority level of low (indicated by the green text). Clicking on the task enables you toggle through various priority levels including medium (indicated by orange text) and high (indicated by red text).
* Tasks with higher priority levels are automatically moved to the top of the to-do list relative to lower priority tasks.
* There are filters to view tasks from a specific priority level.

## Explanation
* I incorporated the search functionality because I believe it is an efficient way to go through your tasks when you're looking for a specific one. There can be times where there are simply too many tasks on your list to where you're wasting time scrolling through all of them. In addition, it provides the opportunity to use a naming convention that could result in using the search function to act as a dynamic tag filter. For example, if all of the tasks related to Company A were named "Company A: ..." and the all of the tasks related to Company B were named "Company B: ...", etc., searching "Company A" would yield only the tasks related to that specific company. In a way, this addition provides multiple functionalities in one feature.

* I implemented various priority levels in order to help users organize their tasks. There may be times where certain tasks have a higher level of urgency than others and I wanted this application to be able to account for that. Not only can you set the priority level of high, medium, or low and then use the corresponding filter to view only those tasks, you can also see that the tasks are automatically organized with the highest priority ones being at the top. Sometimes the priority of a task may change so I implemented the feature to where the priority level can be toggled by single-clicking the task itself instead of clicking a different button. In order to show the user feedback of the priority level changing as well as help them visually keep track of the current level, I chose to change the color of the text accordingly. I believe this style helps keep the interface clean while providing a more dynamic and aesthetically pleasing experience.

## Highlights
* In terms of styling, I wanted to keep the interface simple... and well, Foolish! I intentionally kept the interface simple with a white background because this application is a to-do list and needs to be efficient. Adding landscape backgrounds could be nice, but it is unnecessary and could even be distracting. Instead, I chose to use multiple colors in the application. I believe that the color changing logo provides a more dynamic feel to the page when looking over your list and the color scheme stays true to The Motley Fool. 

* I added a quote to remind users that while this list does contain important tasks, there is more to life beyond it. Since there may be times where users feel stressed or overwhelmed, I think it is important to provide some encouragement and support. 

* Additionally, I believe color-coding tasks can help users visually see which tasks may be more urgent so I incorporated the red, orange, and green text to help users differentiate when viewing all the items at once. 

## Possible Improvements
* An improvement I would make with this application would be providing a more personalized experience for users. If this application allowed users to create an account, it could include more personalized messages and even enable users to view their tasks on any device they login to. Additionally, this would provide the opportunity to enable notifications that could be pushed to the user via text message or email.
* Being able to reorder the tasks manually could be another improvement for those users who want them in a certain order.
* Another idea for a feature could be setting when the task needs to be completed by for those tasks that have a set due date and time. With this feature, the application could then change the priority level of the task according to how much time is left.





