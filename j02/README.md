# The Jetbrains Suite

Jetbrains is a company that produces various IDEs for developers. IDE stands for Integrated Development Environments, which can be boiled down to any text or asset editor designed for a specific set of languages. As we can see, Jetbrains makes a lot of them:

<img src=../assets/jetbrains_website.png alt="jetbrains website">

A lot.

For the sake of keeping things concise I will be looking specifically at IntelliJ, their most popular IDE. However, one of the really nice features of all of these editors is that they follow a very consistent design language. I started with IntelliJ IDEA, but when I needed to do C/C++ work I decided I'd try to use CLion. I found great comfort when the UI was very familiar to IDEA, if identical. When I wanted to get into web development I tried WebStorm, and again, felt familiar and comfortable. The design consistency between all of their products is something that cannot be understated.

<img src=../assets/idea_main.png alt="IntelliJ IDEA main window">

This is the main window you load into when you're working on a project. It has a lot of familiar elements to some advanced text editors like VSCode. A folder navigation panel on the left side. An editor pane with open files in tabs along the top edge. One of the main appeals that IDEA, and all other Jetbrains IDEs has to me is in the top left, the run configurations toolbar. In every IDE you can set up a run configuration and debug your code by creating breakpoints on lines by clicking to the right of the line number. A lot of other IDEs have this, but none have it integrated so well with the language. When you finally hit the debug button, and that line of code is reached it brings up an immensely useful details panel on the bottom, with a list of all the variables in scope:

<img src=../assets/idea_debug.png alt="IntelliJ IDEA with debugger">

In addition to the variables list display, the value of the variables at the moment before the breakpoint was hit is also displayed next to the line that was executed. Clicking on these allow you to modify the value, allowing for you to put the code in an irregular/edge case. In my experience no other editors have such a well designed debugger that requires such little configuration to get working. 

An additional advantage that Jetbrains products has is a vast extension suite in the marketplace. This can be used to find extensions that help add niche features like support for Minecraft modding, or an extended Lua engine so you can write Lua code in IDEA. One of the real places that the exensions marketplace shines is for keymaps. While writing this entry I was going to complain about how I have yet to find how to do multi-cursor actions like one can do with ctrl+d in VSCode. As it turns out instead of changing individual keybinds, you can change the whole keymap layout with a dropdown menu. Initially this dropdown didn't have a VSCode option, but there was a link to the extensions marketplace that lists out all of the keymaps. Near the top was a VSCode one. On installing that multi-cursor support worked perfectly:

<img src=../assets/idea_keymap.png alt="IntelliJ IDEA keymap menu">
<img src=../assets/idea_extensions.png alt="IntelliJ IDEA keymap extension marketplace">

* ✅ Effective - Yes. Does what any other IDE does, and more.
* ✅ Efficient - Yes. Especially with how powerful the debugging interface is.
* ✅ Safe - Yes. About as safe as any other IDE.
* ✅ Satisfying - Yes. The debug interface seriously feels so good when compared to other IDEs.
* ✅ Learnable - Yes. Notes and links to places that can also affect certain settings are all over the place.
* ✅ Memorable - Yes. Especially when you change settings to your preference.
* ✅ Useful - Yes. It's an IDE.
* ✅ Error Tolerant - Yes. Errors within your code don't affect the editor. Moreover errors in settings can easily be reverted, and red highlights present serious issues.