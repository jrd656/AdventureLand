# How to improve potion consumption:

So you've been over to the [discord channel](https://discordapp.com/channels/238332476743745536/238332476743745536) for AdventureLand, and you've read through all of the guides on the #Welcome page, and you're still stuck as to how you can possibly start improving on the default code you've been given?

Well, you're not alone. In this guide I'm going to try guide you through the steps you can take to delve into the AdventureLand code and then start to build up a few of our own functions.

## The use_hp_or_mp() Function:

So at some point, you'll have looked through the [guide on Steam](https://steamcommunity.com/sharedfiles/filedetails/?id=1640326394) and read the following:
![Steam Guide](/images/SteamGuideGoals.png)

'improve potion consumption' you say? OK...

And then you've gone back to the game screen and clicked the CODE button in the top-right of the screen. At the top of the default javascript code, you'll see the following:
![use_hp_or_mp snippet](/images/use_hp_or_mp-function.png)

So - how do we interrogate this "The use_hp_or_mp()" code and discover how to optimise it?

Well, there's a [handy guide provided on reddit](https://www.reddit.com/r/AdventureLand/comments/58yp8e/tutorial_using_chrome_to_help_you_code/), which shows how we can use Developer Tools to find and view the javascript files that power the game.

BUT, there is a catch. For some reason (at the time of writing), the runner_functions.js file wasn't viewable in Developer Tools. Fortunately, however, the creater of the game [has made the file available on his github](https://github.com/kaansoral/adventureland/blob/master/runner_functions.js).

I downloaded the file and opened it in VS Code. Use ctrl+f to find use_hp_or_mp, and... bingo:
![use_hp_or_mp function](use_hp_or_mp().png)






## collapsible markdown?
<details><summary>CLICK ME</summary>
<p>
#### yes, even hidden code blocks!
  
```python
print("hello world!")
```
</p>
</details>
