Immersive Board V16 - Ready-to-upload package

Built from V15.

New in V16:
- The lap / level-completion system is now linked to the win conditions.
- Single-level boards can use a score target to trigger the winner screen.
- Multi-level boards use the final level as the true win condition: the first active player to complete the final level wins.
- If only one active player remains after eliminations, that player wins automatically.
- The winner title and winner message are editable by the teacher in Edit Mode > Game flow and win conditions.
- Example tile reward values have been cleaned up:
  - Bonus tiles default to 50 points.
  - Question, task, challenge, prompt, info and event-style tiles can use smaller completion rewards, typically 10-30 points.
- Activity points are only awarded when the teacher/participant confirms the task was completed correctly using the award button in the pop-up.

Recommended flow:
1. Use the Home screen to start or open Team Setup.
2. Use Edit Mode to change board media, tiles, task decks, event cards and win settings.
3. For a one-level board, set a score target. When a team reaches it, the winner screen appears.
4. For a multi-level board, players complete laps and progress through levels. On the final level, the first player back to START/END wins.

Existing features still included:
- Clean default board with regular tiles and checkpoint-style corners.
- START acts as START / END.
- Lap rewards: 1st = 200, 2nd = 150, 3rd = 100, final player in countdown = 50.
- Multi-level freezing, countdown and elimination logic.
- Touch-friendly immersive room layout.
- Edit sidebar sections.
- Teacher PIN lock.
- Custom teams and token images.
- Scoreboard inside the centre artwork area.
- Multiple-choice and open-answer questions.
- Task card decks.
- Random event cards.
- Move and win sound settings.
- Leaderboard / podium screen.

How to use:
1. Upload index.html and the assets folder to a GitHub repository.
2. Keep index.html at the root of the repository.
3. Enable GitHub Pages: Settings > Pages > Deploy from branch > main > root.
4. Use the GitHub Pages link inside Immersive Studio.

Keyboard shortcuts:
- Space: roll dice
- M: move selected token by last dice roll
- 1 / 2 / 3 / 4: select team token
- Left / Right arrows: move token backward / forward
- E: open / close Edit Mode
- T: open / close Teacher Controls
- H: open Home screen
- N: next level
- P: previous level
- Y: end turn
- Esc: close pop-ups and drawers
