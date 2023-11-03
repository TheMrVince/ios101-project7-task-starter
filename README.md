# Project 7 - *Task App*

Submitted by: **Vince Hernandez**

**Task App** is an app that creates tasks and marks them on a calendar.

Time spent: **3** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] App displays a list of tasks
- [x] Users can add tasks to the list
- [x] Session persists when application is closed and relaunched (tasks dont get deleted when closing app) 
  - [x] Note: You have to quit the app, not minimize it, in order to see the persistence.
- [x] Tasks can be deleted
- [x] Users have a calendar view via navigation controller that displays tasks	


The following **additional** features are implemented:

- [ ] Tasks can be toggled completed
- [ ] User can edit tasks by tapping on the task in the feed view
- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

<div>
    <a href="https://www.loom.com/share/fd31e7ddcec841dcbf1fadba74cc4da9">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/fd31e7ddcec841dcbf1fadba74cc4da9-with-play.gif">
    </a>
  </div>

## Notes

Challenges that were present when making this application would be the trying to use the JSONEncode functions to try and save data. I was able to resolve the issue by making the 
the struct codable, making the JSONEncoder work.

## License

    Copyright [2023] [Vince Hernandez]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
