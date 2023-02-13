# Programmatic-UI
A programmatically written app.
My first project after switching from StoryBoard to Programmatic UI. This app has no functionality. The app is purely Programmatic and contains UI elements such as labels, buttons, views. Created to practice constraints, item positioning. 
The structure of code:
- answersLabel.setContentHuggingPriority(UILayoutPriority(1), for: .vertical): It sets priority of the UI element to 1, being the lowest value, it means when VC tries to fit all the components by their constraints, sometimes some elements get stretched or shrinked, in those situations the first elements to go under the change are the items of Priority 1 with respect to vertical axis.
