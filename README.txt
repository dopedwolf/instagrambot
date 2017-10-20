1. Open instagram on computer (make sure you are signed in)
2. Find a #tag you want to target (the more posts the better)
3. Click on a post on the most recent section
4. Copy and paste bot in to the Developer Tools console
5. Press enter and let it run on the background.

The bot's deafult stopping point is 25 posts. This prevents the possibility of chrashing.

This can be altered by simply changing the 25 in:

  if (likeCount < 25) {
       setTimeout(doLike, nextTime);
   }
