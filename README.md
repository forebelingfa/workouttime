# Workout Time!

Workout Time! is a cross-platform app for tracking timed workout routines.

## Installation

[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png" height="75" alt="Get it on F-Droid">](https://f-droid.org/packages/es.ideotec.workouttime/)

## Usage

### Home Screen
Lists all workouts (the app comes with two predefined workouts, and others can be created or imported). Tapping on the pencil icon on the left of a workout will go to the Edit Screen, tapping on the title or duration of a workout will start it from the beginning, tapping on the "⌄" symbol on the right will show a list of the exercises it contains. Each exercise has a preparation/rest time before it (shown on the left), and a duration (shown on the right). Tapping on an exercise in the list will start the workout at that exercise. To add a new workout, tap on the "+" button on the bottom right corner and select "Create" to build it from scratch or "Import" to load a workout saved in JSON format. At the top-right corner of the home screen are two icons: a calendar with a checkmark in it (tapping this will go to the Log Screen) and a gear (tapping this will go to the Settings Screen).

### Workout Screen
When a workout is running there is a progress bar at the top showing the current point in the workout, with the time elapsed on the left and the time remaining (indicated with a "-") on the right. In between these two times are a series of dots that represent the exercises in the workout, with the current exercise highlighted in blue. Below this is the name of the current exercise. During the exercise preparation time the name will have "Get ready for" before it (tapping on this will skip the preparation and begin the exercise). Below the exercise name is a stopwatch showing the current progress in that exercise, with the remaining time in the middle. Tapping on the stopwatch will pause the workout (indicated by blinking time inside the stopwatch), and tapping again will resume it. At the bottom of the screen is the name of the next exercise. Tapping on this will skip to the next exercise.

### Edit screen
Lists all exercises in a workout, with the preparation time on the left and the duration on the right. To change an exercise, tap on it and the two times will become spinners that can be swiped up or down to modify the time. Long-pressing on the spinner allows modifying the number with the keyboard (must be a number of seconds without any punctuation). Tapping on the exercise name will bring up the keyboard to edit it. Under the name are three icons: an up arrow to move the exercise higher in the list, a down arrow to move it lower, and a trash can to delete the it. In the top-right corner of the screen are two icons: a download icon to save the workout in JSON format to the Downloads folder, and a trash can to delete the entire workout.

### Log Screen
Lists all the executions of workouts, with the date and time on the left and the name of the workout on the right. At the top-right corner of the screen is a download icon that will save this list in JSON format to the Downloads folder.

### Settings Screen
This screen has three dropdown menus to select the sound to play for the last 3 seconds of preparation/exercise time, at the start and end of each exercise, and at the end of the workout. There are 4 options for each: nothing, a beep, a ding, or an applause.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)