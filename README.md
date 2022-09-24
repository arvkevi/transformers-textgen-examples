# Text generation with transformers

1. Identify text generation tasks (subfolders).
2. Process the text into a format suitable for text generation via distilgpt2.
3. Fine-tuning the casaul language model on Google colab.
4. Generate text by loading the model from the HuggingFace model hub.

# Example outputs

Full outputs can be found in the subfolders for each task.

## Python Bytes

```

```

## NBA Game play-by-play

Generated text from a model fine-tuned on the play-by-play descriptions from the Boston Celtics and Golden State Warriors during the 2021-2022 NBA season.  

```
1 11:45 0-0 K. Looney misses 2-pt layup from 4 ft (block by R. Williams)
1 11:43 0-0 Defensive rebound by J. Hart
1 11:32 0-0 Turnover by J. Clarkson (bad pass; steal by J. Poole)
1 11:18 0-0 Personal foul by K. Looney (drawn by J. Poole)
1 11:14 0-0 J. Poole misses 2-pt jump shot from 13 ft
1 11:11 0-0 Defensive rebound by K. Looney
1 10:57 0-0 R. Williams misses 3-pt jump shot from 25 ft
1 10:54 0-0 Defensive rebound by R. Langford
1 10:45 0-0 J. Clarkson misses 2-pt jump shot from 9 ft
1 10:43 0-0 Defensive rebound by K. Looney
1 10:30 0-0 Personal foul by J. Poole (drawn by D. Lee)
1 10:30 0-0 A. Wiggins enters the game for G. Payton
1 10:15 0-0 M. Moody misses 3-pt jump shot from 27 ft
1 10:13 0-0 Defensive rebound by Team
1 9:03 0-0 Turnover by K. Looney (bad pass; steal by R. Langford)
1 9:00 0-0 D. Lee misses 2-pt jump shot from 19 ft
1 8:57 0-0 Defensive rebound by R. Langford
1 8:46 0-0 Personal foul by K. Looney (drawn by J. Clarkson)
1 8:45 0-0 Violation by Team (kicked ball)
1 8:33 0-0 J. Poole misses 2-pt jump shot from 6 ft
1 8:31 0-0 Offensive rebound by Team
1 8:27 0-0 Turnover by K. Looney (offensive foul)
1 8:23 0-0 A. Wiggins misses 2-pt jump shot from 19 ft
1 8:22 0-0 Offensive rebound by K. Looney
1 8:21 0-0 J. Poole misses 2-pt layup from 2 ft (block by K. Looney)
1 8:18 0-0 Defensive rebound by R. Langford
1 8:11 0-0 Shooting foul by R. Langford (drawn by R. Langford)
1 8:11 0-0 R. Langford misses free throw 1 of 1
1 8:09 0-0 Defensive rebound by R. Langford
1 8:09 0-0 R. Langford misses free throw 2 of 1
1 8:08 0-0 Offensive rebound by Team
1 8:05 0-0 Shooting foul by K. Looney (drawn by D. Lee)
1 8:05 0-0 D. Lee misses free throw 1 of 2
1 8:05 0-0 Offensive rebound by Team
1 8:05 0-0 D. Lee misses free throw 2 of 2
1 8:02 0-0 Defensive rebound by K. Looney
1 8:01 0-0 Personal foul by J. Clarkson (drawn by D. Lee)
1 7:51 0-0 Shooting foul by K. Looney (drawn by D. Lee)
1 7:51 0-0 D. Lee misses free throw 1 of 2
1 7:51 0-0 Offensive rebound by Team
1 7:51 0-0 D. Lee misses free throw 2 of 2
1 7:49 0-0 Defensive rebound by K. Looney
1 7:46 0-0 Turnover by D. Lee (bad pass; steal by K. Looney)
1 7:31 0-0 J. Poole misses 3-pt jump shot from 26 ft
1 7:29 0-0 Defensive rebound by A. Wiggins
1 7:19 2-0 K. Looney makes 2-pt layup from 4 ft (assist by D. Lee)
1 7:12 2-0 J. Poole misses 2-pt jump shot from 16 ft
```