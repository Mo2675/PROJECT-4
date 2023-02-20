Overview
You will be completing a scavenger hunt app. This app has a list which requires the user to attach photos based on the task. After attaching the photo to a task, the app shows the user where that photo was taken in a map.

Screenshot of app with core features implemented

🎯 Goals
By the end of this assignment you will be able to...

Use PHPicker to select photos and get photo data from the photo library
Use MapKit to display custom annotations on a map
Required Features
Task List Screen
Users should be able to view a list of tasks to be completed
For simplicity, you can create your own hardcoded Task data models
Users should be able to tap into a task and be navigated to the task detail screen
Tasks that have been completed should be visually distinguished (see task detail view)
Task Detail Screen
Users should be able to view the title, description, and possibly the attached photo of the task
Users should be able to attach a photo to the task
Doing this marks the task as completed with a visual indicator and shows the location of the photo inside of the map
The completed indicator should also be visible in the task list
After completing the task on detail view, the list page should reflect it was completed
Stretch Features
Give the user the option to open the camera instead of choosing from the photo library
Use the UIImagePickerController class to show the camera. You will need to build to device in order to test this.
Note: You can also use this class to open the photo library. However that will be deprecated soon. You should only be using UIImagePickerController to present the camera.
Resources
MapKit
PHPicker
💡 Hints
I cannot get the location data from a photo.

Make sure you're selecting a photo that actually has location metadata. Also, make sure that the user has granted full access to the photo library.
My app crashes when presenting PHPickerViewController

Make sure to include the NSCameraUsageDescription key in your app’s Info.plist file similar to what was done in lab.
📬 Submitting Your Project
📄 PROJECT 4 README TEMPLATE
🔗 Submitting Coursework step-by-step instructions
✔ Submission Checklist
Check if you're ready to submit with the following questions:
Does your app have all of the Required Features?
Can you see your latest code on GitHub?
Does your README use the provided README TEMPLATE?
It is important that you follow the same layout as the README template so that we can easily access your work.
Be sure to check off each feature that is implemented in your submission by changing [ ] to [x].
Did you include a GIF (or Video) walkthrough? (NOT only screenshots!)
When going to your main repository page on GitHub, can you see your README and does your GIF walkthrough start playing?
Is your repository private with codepathreview as a collaborator?

If you answered yes to all of these questions, you are ready to submit!

Look for the "Submit" button at the top of this page.
