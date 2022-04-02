# xkcd2601

## fast'n'loose edition

**Disclaimer:** This code has a ton of typos. It should be used only as a reference.

Adapted from Pgn674's machine speech-to-text transcript.

(Note: it was run in Berkeley LOGO aka `ucblogo`)
(Further notes: the typos should be easy to spot - in general points should be roughly in a line.)
(The parameters to `CUBIC` are basically `X1 Y1 X2 Y2 X3 Y3`)
(So if you have `400 ??? 600 ??? 800 ???` that's ok. if you have `400 ??? -6 ??? 800` that's probably a typo.)

This is a project to transcribe xkcd #2601, the April Fools post for 2022, to runnable logo code.

### Running the code:

It runs in FMSLogo, which is windows only, sadly. But it might run on your
logo variant of choice.

If you can find a logo that is open source, multi-platform, renderers
beautifully, doesn't require an installer on windows, and runs this code with
a minimum number of changes, i'll happily convert the project over to that.

(I first tried aUCBLogo, which seemed nice, but it started crashing on the
input once there were a certain number of comments, which seemed like a red flag)

To run this in FMSLogo, open the file, then in the console, type **xkcd**.

To open the file for editing in FMSLogo, you press the inscrutable "Edall"
button. You must then save and close your edit before running it again, or
highlight lines in the editor and hit ctrl-R to run them immediately.

Like I said, would love a decent alternative to this logo interpreter.

### Aiding transcription

If you want to aid transcription, take a look at the code to get a sense of what
things should look like. Make what you write look like that. Claim a time period in
the [file](https://xkcd.com/2601/radio.mp3) (in chunks of 10 minutes) with a bug report.
File your transcription with a pull request.

In the pull request, start and end your contribution with a comment showing the time, and
add additional timestamps every 5 minutes or so, which will make it easier to fix transcription
bugs. They should look like e.g.

**; NOTE: [00:40:00]**

If you don't know how things should be typed out, check the current code or some logo docs.
[This is what I've been using.](http://people.eecs.berkeley.edu/~bh/usermanual)

Try to run your code before submitting by sticking it at the end of what we already have. Make sure it looks sane.

If you don't have a github account and want to help, you can message me on reddit if you
have an account there, and I'll update the bugs and such accordingly.

### Screenshot

![fast and loose](./screens/fnl1.png)
