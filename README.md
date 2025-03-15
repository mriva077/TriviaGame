# Project 5 - *Trivia Game*

Submitted by: **Mauricio Rivas**

**Trivia Game** is an app that allows users to test their knowledge by answering trivia questions across various categories, difficulties, and formats. Users can customize their trivia experience before starting a game and receive a final score based on their performance.


Time spent: **48+** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] App launches to an Options screen where user can modify the types of questions presented when the game starts. Users should be able to choose:
  - [x] Number of questions
  - [x] Category of questions
  - [x] Difficulty of questions
  - [x] Type of questions (Multiple Choice or True False)
- [x] User can tap a button to start trivia game, this presents questions and answers in a List or Card view.
  - Hint: For Card view visit your FlashCard app. List view is an equivalent to UITableView in UIKit. Much easier to use!
- [x] Selected choices are marked as user taps their choice (but answered is not presented yet!)
- [x] User can submit choices and is presented with a score on trivia game
 
The following **optional** features are implemented:

- [ ] User has answer marked as correct or incorrect after submitting choices (alongside their score).
- [ ] Implement a timer that puts pressure on the user! Choose any time that works and auto submit choices after the timer expires. 

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<div>
    <a href="https://www.loom.com/share/ab1a7346dc5a43e28d6c372e53f2f16c">
      </a>
    <a href="https://www.loom.com/share/ab1a7346dc5a43e28d6c372e53f2f16c">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/ab1a7346dc5a43e28d6c372e53f2f16c-98a964fcfe4f4ab6-full-play.gif">
    </a>
  </div>
## Notes

Describe any challenges encountered while building the app.

### Challenges Encountered:
- Fetching and parsing trivia data from an API while ensuring smooth UI updates.
- Managing **state updates** for selected answers without affecting overall performance.
- Adjusting UI elements to be visually appealing and correctly aligned across different screen sizes.
- Implementing the **slider-based difficulty selection** in a way that is both functional and intuitive.

## Future Improvements:
- Implement **real-time feedback** (correct/incorrect answers) after submission.
- Add a **countdown timer** to create a more challenging experience.
- Store user scores using **Core Data** or **UserDefaults** to track progress over time.


