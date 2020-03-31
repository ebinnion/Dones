# Dones

This workflow was created as a simple tool to log tasks I had taken in a given day. It's modeled loosely off of other tools that I had previously used to track dones, but it write to a local file for simplicity.

In the workflow environment variables, you need to specify a path. My path is ~/Drobox/Eric/Dones for reference, which I'll export as an example.

Once you've set that, you can then use something like, "done Updated the workflow description".

This workflow will then append to a file, with the current date as the title, first creating if necessary within the directory specificied by the workflow environment variable. That entry will also contain the current time so that you can reference it later. As you add dones throughout the day, they should go to the same file. But, on the next day of work, if you add a done, it should go into a new file with that day's date.

If you happen to use this in the wild and have some feedback, feel free to get in touch via my personal blog at [https://eric.blog/contact](https://eric.blog/contact).
