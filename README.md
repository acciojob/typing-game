# Typing Game

<p>One of my favorite time passing game is touch typing. Good command of touch typing is a very important skill, especially when it comes to productivity. Sometimes you can feel it too. 
 Touch typing gives leverage when you are competing with others. Also, it's fun, isn't it?</p>
 <strong>Task: <i>Create Touch Typing Game</i></strong>
 <p><i>Description</i>: Create a typing game which has a timer and show the typing speed in words per minute(WPM)</p>
 

 <h3>Acceptace criteria</h3>
 <li>Timer element ID <code>timer</code></li>
 <li>WPM element ID <code>wpm</code></li>
 <li>Container element ID <code>container</code></li>
 <li><code>correct</code>, <code>incorrect</code> classes should be used appropriately to mark letters if user typed some letters.</li>
 <li>Initially timer and wpm should be zero(0)</li>
 <li>User can start the game clicking on <i>container</i> element</li>
 <li>In order to start the game, start the timer and user should be able to type and see their progress in the wpm element</li>
 <li>User can stop the game by clicking outside of <i>container</i></li>
 <li>In order to stop the game, stop the timer and set to zero(0), pause the wpm whatever it's value was and remove classes <code>correct/incorrect </code>from letter of the quote (make it like new rendered quote)
 </li>
 <li>If user typed the rendered quote completely (doesn't matter correct/incorrect), automatically render new quote and set timer to zero(0)</li>
 <li>Update the timer after each second by <strong>1 (one)</strong> when game stated. Timer is showing the time passed in second.</li>
 <li>Given formula should be used to calculate speed(wpm)</li>
 <li>You should be using this <a href="http://api.quotable.io/random">API</a> to get quotes. Be mindful for special letters/symbols</li>
 <li>Use <code>fetch()</code> to make API calls</li>
 <li>Use <code>Math.round()</code> in order to round wpm.</li>
 <li><strong>Time-Elapsed (sec) </strong> should be calculate using <code>Math.floor((new Date() - startTime) / 1000)</code>startTime ->Timestamp(when timer started)</li>
 <li><strong>WPM</strong> should be calculating using <code>Math.round(parseFloat(correctStrokes()) / 5.0 / (parseFloat(<strong>Time-Elapsed(sec)</strong>) / 60.0));</code> Formula is shown in the picture</li>
 <li>Update the wpm on each-stroke(doesn't matter correct/incorrect)</li>
 <li>Input should be given to <code>body</code> tag. Hint add event listner to document.</li>
 <li>Use <code>keydown</code> event for input. Hint: <code>e.key/e.keyCode</code></li>
 <li>Try to make it interactive/engaging/awsome. <i>Happy coding :)</i></li>
