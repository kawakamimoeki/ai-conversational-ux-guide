# Waiting time

Since the advent of computers, people's waiting time when using computers in their daily lives has increased and decreased according to a certain pattern. The pattern is that processing time for the same operation improves with the development of computing technology, but at the same time, new processing content (text, images, communication) is created, and waiting time increases each time.

The emergence of LLM falls under the latter of these timings, and for at least general users, the experience of longer waiting times than before has not been long.

Latency should be no more than about 3 seconds if stream output, as mentioned above, is achieved, but there is room for discussion about where to divert the user's attention during that time.

A common method is a loading animation. For conversation UX, you could display a cursor in the assistant's message box and blink it.

In addition, for conversation UX, other information besides the messages is still available, so it may be a good idea to design the screen to allow for other tasks or viewing of other information while waiting.
