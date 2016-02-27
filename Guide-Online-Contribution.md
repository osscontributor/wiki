# Contributing to the Wiki directly from the browser
In an effort to make contributing to the wiki and to [FreeCodeCamp](https://github.com/FreeCodeCamp) in general, this tutorial will walk you though the process step by step.

## Requirements
1. Stable internet connection.
2. A [GitHub](https://github.com) Account. If you don't have one then click [here](https://github.com/join) to create one.
3. Learning to [write on Github.](https://help.github.com/categories/writing-on-github/) A quick referenced to [GitHub Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Instructions
Navigate to the [Wiki.](https://github.com/FreeCodeCamp/wiki) You will encounter something similar to the image in figure _1a_ bellow. This will give you three options to add changes for your [pull requests.](https://help.github.com/articles/using-pull-requests/) They are by no means numbered in the way you should try then, I just went from left to right. Each one have their purpose.

_Figure 1a_![Imgur](http://i.imgur.com/GpDDnzs.png)

### 1. New Pull Request Button
This is used to create [pull requests](https://github.com/FreeCodeCamp/FreeCodeCamp/wiki/How-To-Create-A-Pull-Request-for-Free-Code-Camp) from files that are already in existing branches, no really for adding new files. So if you are looking to add new files then check the other options.

### 2. New File Button
This is the option to choose if you want to directly create your files and submit a pull request from the browser. Unlike the **New Pull Request** button, this option allows you to create new files.

### 3. Upload Files Button
If you have already created the files, which should be `.md` files for **Markdown** or if you are contributing source code then feel free to use the adequate file extension.

After you select it, you will see something similar to _Figure 3a_ bellow. You have the following options:
- ** Drag or select files to upload:** This allows you to actually add the files, any files so be careful with what you upload.
- **Remove Files:** If you press the `x` it will remove the unwanted files before you proceed.
- **Add Title:** This will let you add a title for your pull request. Please try to use a self descriptive but short title. You will have a place to add as much details as you like.
- **Add Details:** Bellow the title you can add extra information using Github markdown. This means you can add links, images, videos, checklist, and everything that is supported. Please see link on the Requirements section.
- **Select how to contribute:** If you have write access like me then you can commit directly which is strongly advised not to do even for the core team. However, regular users will be unable to select this option anyway. The best way is to create a new branch for the pull request as seen on _Figure 3b_. This allows you to write a name for the branch. It is suggested to use a descriptive name that will give a glimpse of what the branch is about, for example `wiki-guide` for this guide, or `Palindromes` for an article about palindromes. The name shown on the image in an example of a **bad name!**
  - _Figure 3a_ ![Uploading Files](http://i.imgur.com/PJ2kp5k.png)

After you select your files, you will be presented with a screen like _Figure 3b & Figure 3c_ where you have the options to:
- **Change Base branch:** Always select master unless you know what you are doing, the base should be the target branch.
- **Compare to branch:** This should be the branch you create for your pull request.
- **Details:** As before you will have a chance to change the title and details which will have the previous values.
  - _Figure 3b_![Creatign PR](http://i.imgur.com/rHfSVcX.png)

- **Files Preview:** You will have the chance to see what your files look like from _Figure 3c_. **Note** that here I changed the actual pull request for another one with a better branch name and a draft of this guide instead of just random images.
- You can select to view the code with differences between the previous version and the new one if you are modifying an existing file.
- The current view is the Rich difference that allows to view the changes on the same file, red for deletions, green for additions.  Lastly you have the option to view the file as if it was live.
  - _Figure 3c_![File Preview](http://i.imgur.com/oYS8ZNr.png)

Next is to click on `Create pull request`. it is the green button and it will take you to view your pull request. it will look similar to _Figure 3d_ bellow.
- _Figure 3d_![Created PR](http://i.imgur.com/PSx5NPU.png)

The first thing you will notice it the title with the pull request number. in the example it is `#393`. Next is the status of the pull request, It will either be `Open`, `Closed` or `Merged`.

You can click on the tabs to view the commits, always try to have everything in one commit or as fewer as possible it you have a good reason to have more than one commit. If you have multiple commits and need to **squash** them then follow [these](https://github.com/freecodecamp/freecodecamp/wiki/git-rebase#squashing-multiple-commits-into-one) instructions.

That's it, you can reference people by adding `@` before their name. You can reference other issues or pull request by adding their id, which would be `#393` for the example from _Figure 3d_.

If your pull request closes an issue then you can add `Closes #` followed by the issue number, once the pull request is merged then issue will be automatically closed. You can edit the title or details if you are the one who created the pull request. _Figure 3d_ shows how it will look for someone who did not create it.

The following is how it looks when you are able to edit your own pull request.

_Figure 3e_ ![Edit PR](http://i.imgur.com/NPgXkiz.png)

Always delete the branch after the pull request has been merged or closed. There might be cases where this will be done automatically but if for whatever reason you see something like in _Figure 3f_ then press delete.

_Figure 3e_ ![Delete Branch](http://i.imgur.com/vePGN3Y.png)
