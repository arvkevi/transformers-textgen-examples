# Text generation with transformers

1. Identify text generation tasks.
    - Each of the subfolder in this repo are different applications of text generation.

2. Process the text data into a format that is suitable for text generation.
    - Notebooks in each subfolder prepare the data for training.
    - For example, gpt2 expects <|endoftext|>tokens at the end of each text.

3. Fine-tuning the casaul language model on Google colab
    - Links to each colab notebook are in the subfolder's README.
    - push the fine-tuned model to hugging face hub.

4. Generate text by loading the model from the HuggingFace model hub

# Example outputs

Full outputs can be found in the subfolder, but here's an example of the first 100 lines of the Python Bytes podcast episode and a play-by-play of an NBA game between the Boston Celtics and Golden State Warriors.

## Python Bytes

```

```

## NBA Game play-by-play

Generated text from a model trained on the play-by-play descriptions from the Boston Celtics and Golden State Warriors during the 2021-2022 NBA season.  


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
```