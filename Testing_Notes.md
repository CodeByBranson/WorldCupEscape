# World Cup Escape — Testing Notes

## 1. Purpose

This document records the testing process for World Cup Escape, an Excel VBA maze game.

The purpose of testing is to check that the game starts correctly, responds to player input, handles collisions, updates scores and lives, and allows the player to progress through the stages.

## 2. Test Environment

Complete these details when testing the version you intend to publish.

- **Game version:** ____________________
- **Workbook filename:** ____________________
- **Date tested:** ____________________
- **Operating system:** ____________________
- **Microsoft Excel version:** ____________________
- **Tester:** ____________________

## 3. Test Status

Use the following statuses:

- **Not Tested:** The test has not been performed.
- **Passed:** The observed result matched the expected result.
- **Failed:** The observed result did not match the expected result.
- **Blocked:** The test could not be completed.

## 4. Functional Testing

### Test 1: Opening the Game

**Procedure:**
1. Open the workbook in desktop Microsoft Excel.
2. Follow the appropriate security prompts.
3. Check whether the game interface loads.

**Expected result:** The workbook opens and the game interface appears without unexpected errors.

**Status:** Not Tested

### Test 2: Starting a Game

**Procedure:**
1. Open the game interface.
2. Select Start.
3. Observe the maze and game information.

**Expected result:** A new game starts and the required game elements are displayed.

**Status:** Not Tested

### Test 3: Player Movement

**Procedure:**
1. Start the game.
2. Press each arrow key.
3. Observe the player's movement.

**Expected result:** The player moves in the intended direction when a valid movement is made.

**Status:** Not Tested

### Test 4: Collision Detection

**Procedure:**
1. Move the player towards a wall or obstacle.
2. Observe the result.
3. Repeat with other relevant obstacles.

**Expected result:** The collision behavior matches the game's rules.

**Status:** Not Tested

### Test 5: Lives System

**Procedure:**
1. Start a game.
2. Trigger a collision that should cause a life loss.
3. Check the Lives display.

**Expected result:** The lives counter updates correctly and any intended visual feedback appears.

**Status:** Not Tested

### Test 6: Goals and Scoring

**Procedure:**
1. Start a game.
2. Collect a goal or scoring item.
3. Check the goal counter and score.

**Expected result:** The relevant counters update according to the scoring rules.

**Status:** Not Tested

### Test 7: Stage Completion

**Procedure:**
1. Navigate to the exit.
2. Complete the current stage.
3. Observe the next stage.

**Expected result:** The game recognises stage completion and advances correctly.

**Status:** Not Tested

### Test 8: Stage Progression

**Procedure:**
1. Complete each stage in sequence.
2. Observe the stage number, difficulty, lives, and score.
3. Confirm whether progress carries forward as intended.

**Expected result:** The game progresses through the available stages and applies the correct rules.

**Status:** Not Tested

### Test 9: Losing All Lives

**Procedure:**
1. Start a game.
2. Lose all available lives.
3. Observe the resulting message or screen.

**Expected result:** The game handles the failed attempt correctly and offers the appropriate retry or restart option.

**Status:** Not Tested

### Test 10: Restarting the Game

**Procedure:**
1. Start a game.
2. Select Restart.
3. Observe the maze, score, lives, and stage.

**Expected result:** The game resets or restarts according to its intended rules. If new mazes are intended, confirm that the maze changes when restarting.

**Status:** Not Tested

### Test 11: Pause and Resume

**Procedure:**
1. Start a game.
2. Select Pause.
3. Select Resume.
4. Repeat the actions when the game is already paused or resumed.

**Expected result:** Pause and resume work correctly, and repeated actions do not cause errors or misleading messages.

**Status:** Not Tested

### Test 12: Timer

**Procedure:**
1. Start a game.
2. Observe the timer.
3. Pause, resume, or restart if those features are available.

**Expected result:** The timer behaves according to the intended game rules.

**Status:** Not Tested

### Test 13: High Scores

**Procedure:**
1. Complete a game or achieve a score.
2. Check the high-score section.
3. Close and reopen the workbook if score persistence is intended.

**Expected result:** Scores appear and are formatted and retained according to the implemented rules.

**Status:** Not Tested

### Test 14: Sound

**Procedure:**
1. Open the game.
2. Test any sound or music features.
3. Restart or close the game and check that audio behaves as intended.

**Expected result:** Sound functions correctly without causing unexpected errors.

**Status:** Not Tested

### Test 15: Download Package

**Procedure:**
1. Copy the release files to a separate folder or download them as a new user would.
2. Open the packaged workbook.
3. Follow the player instructions.

**Expected result:** The game can be opened and used from the distributed package.

**Status:** Not Tested

## 5. Bugs and Issues

Record any issues found during testing.

- **Issue:**
- **Stage:**
- **Steps to reproduce:**
- **Expected result:**
- **Actual result:**
- **Severity:**
- **Possible solution:**
- **Status:**

## 6. Release Checklist

Before making the game publicly available:

- [ ] The exact release workbook has been tested.
- [ ] The game starts correctly.
- [ ] Player movement works.
- [ ] Collision detection works.
- [ ] Lives and scoring update correctly.
- [ ] Stage progression works.
- [ ] Retry and restart work correctly.
- [ ] Pause and resume work, if included.
- [ ] Timer and high scores work, if included.
- [ ] Sound works, if included.
- [ ] The downloadable package has been tested.
- [ ] Player instructions match the actual game.
- [ ] The workbook contains no personal or confidential information.
- [ ] Asset permissions and credits have been reviewed.

## 7. Test Summary

- **Tests Passed:** ______
- **Tests Failed:** ______
- **Tests Blocked:** ______
- **Tests Not Tested:** ______

**Overall result:** Not yet assessed.

**Additional notes:** ______________________________________________

Update this document after testing the exact version you plan to publish.