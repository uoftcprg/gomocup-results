Replay files for the tournament 2004 (needs Gomotur program)

2(Bestmove and Hewer2) of 15 brains that took part in the tournament used the new protocol. Because we didn't unfortunately have a debugged manager for the new brains, we decided to let the old protocol brains match each other at first. You can find the results in the folder named Others. Even the old manager has some bugs so some of the.rec files were copied over other . rec files(It seems that it happened when Benjamin or Ai1000 did incorrect move.), so some are duplicates while the originals are missing. When you load the replay, the data in the table is correct, but after playing  the replay, some results in the table change to incorrect.

Then we played single duels of new protocol brains in the new erroneous manager. Duels with Hewer2 and Bestmove are stored in so-named folders. The manager couldn't check timeouts for those duels, so we watched it ourselves. The manager didn't write the information about thinking time to .trn files correctly, so if you watch the replay, it doesn't notify you of the timeouts and SHOWS WRONG SCORE RESULTS! For example, if a brain won four times, but it exceeded the time limit for match once, the results should be 3:1, but the manager shows 4:0. It also shows bad time data. However, the data in .rec files is correct so you may check the time values there(The third number on the line is the time of the turn.).
Timeouts in the duels:
Bestmove exceeded the match limit in the first and the third match with Benjamin and in the third match with Svine2. Hewer2 made a match timeout in the fourth match with Noesis.

Then we matched the worst problem - the duel of Bestmove with Hewer2. Because of some bug, the manager used to freeze after every single match of two pbrains, so we had to play single matches. There was no timeout. The time data is bad again, so you have to read the .rec files.

Reconstructing the real results was real hell :(.