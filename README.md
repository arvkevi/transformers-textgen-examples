# Text generation with transformers

1. Identify text generation tasks (subfolders).
2. Process the text into a format suitable for text generation via distilgpt2.
3. Fine-tuning the casaul language model on Google colab.
4. Generate text by loading the model from the HuggingFace model hub.

# Example outputs

Full outputs can be found in the subfolders for each task.

## Python Bytes

This is not affiliated with the Python Bytes podcast in any way.

From the prompt:  
"fastapi is a great new web framework to easily build web APIs"

```
fastapi is a great new web framework to easily build web APIs. So if you want to add a web application or framework and you want to have an async view, that's awesome. So you can create an API using the same API, they have it manage a whole bunch of requests, all sorts of cool stuff, like flowchart, Mock, Adafruit Red, Flask, Kaggle, Flask, Postgres, Postgres, they all have a couple of features that you can leverage.
 
00:01:25 OKKEN: Yeah.
 
00:01:26 KENNEDY: And one of the things I like about them is that they're based on all the underlying logic and so a lot of those kind of have both interfaces, so they take it up some level for a real application. A lot of that's because of some reasons that some of the the ones I want to implement here are just for MongoDB.
 
00:01:42 OKKEN: Yeah, and there's a some other things that we can do to get MongoDB performance better, which I think the super cool thing about this is how you can do things with the fact that it supports HTTP/2 and Celery, Celery runs on multiple CPUs, so that you don't have to do, you get like hundreds or thousands of requests a second with a certain runtime. So I like this idea of having a little bit of a schedule happening all the time. I don't know what exactly is being served that's going on, because of that. I'm not really sure what it's doing, but maybe it'll be a little bit faster than I would otherwise expect, but it's also cool. So if you want to have some an endpoint like I've mentioned to my team. And then with object-oriented APIs, let me say, you're in a modern app or something, with a couple of reasons. Right. Like, the back end part of the query engine is just coming in, and you really do have to ask the server to do some ID. So that's really nice. So you can take the status of the request that's going on, actually start passing the status, and so it'll receive that result, and then maybe the response will break off when you ask that.
 
00:01:51 OKKEN: Okay, and you could maybe have something like a database back end with the person who creates it.
 
00:01:56 KENNEDY: Oh, my gosh, and that can contain possibly multiple IDs. If you take the status message that you're sending, the database will find that you're listening to it's the user ID at the bottom of the request, right. You want that user ID to be the User Id in the object, but if it's not the user ID at the top of the response, you got to do a debug exit in there. So the ORM error message, or other kind of,
 
00:02:00 KENNEDY: Oh, gosh, even if it's just the bottom of it, it's getting thrown up on it, right? Anyway, it looks really simple. So yeah, it's definitely cool to have a framework that you can build very fast and very consistent. So one of the other things I'm looking forward to at I'm gonna bring up is native encoding, which is not only because you have a bunch of operations that you can go back and write to Windows.
 
00:02:02 OKKEN: Oh yeah, that's cool.
 
00:02:03 KENNEDY: That's cool.
 
00:02:04 OKKEN: I want to talk about a library that takes CPU-intensive data sets and gets a lot of RAM. So the ability to deal with that is great, it's fast, so you can basically put it all together, so I thought I wanted to talk about this bit, and it also talks about my workflow on the server, which is pretty cool. I wanted to talk about a good way to do some sort of parsing of your input, and we're mostly using C to do that. So if you're working with c++ code or C++ you've got a lot of data in front of it, and you've got a little c++ image, and you write an HTTP client and send it back. You don't need a bunch of requests, but you can run that on your servers, and those are some like, we might have to do some kind of faulting or something like this in memory, right. So if it's the user, you know, where's the data? There's lots of file, and a bunch of libraries you can write, you can use them, and they don't have as much overhead of, or RAM, but like a lot of them are out there right there.
 
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