# WEB102 Prework - *Sea Monster Crowdfunding*

Submitted by: **Ahmet Aytac**

**Sea Monster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **5** hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

## Video Walkthrough

Here's a walkthrough of implemented features:


## Notes

### Challenges Encountered:

**Git Setup:**
- Installed Git for Windows and cloned the repository to my local machine

**DOM Manipulation:**
- Used `createElement()` and `appendChild()` to dynamically add game cards
- Implemented template literals for cleaner HTML string generation

**Array Methods:**
- Used `reduce()` to calculate total backers (19,187) and total raised ($800,268)
- Applied `filter()` to separate funded (4 games) and unfunded (7 games) games
- Used `toLocaleString()` for proper number formatting with commas

**Event Handling:**
- Added click event listeners to filter buttons
- Implemented `deleteChildElements()` to clear previous results before displaying new filtered games

**Advanced JavaScript:**
- Used ternary operator for grammatically correct text ("game remains" vs "games remain")
- Applied destructuring and spread operator to extract top 2 funded games
- Most funded: Zoo Tycoon: The Board Game ($442,602)
- Second most funded: How to Read Minds 2 Kit ($147,975)

### Key Takeaways:
- Template literals simplify dynamic content creation
- Array methods like `reduce()` and `filter()` are powerful for data manipulation
- Event listeners enable interactive user experiences

## License

    Copyright 2026 Ahmet Aytac

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
