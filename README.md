# test
BEFORE YOU START:

Welcome! This is a Python-based program that I wrote using PyCharm. Please run it in PyCharm, because I’m not sure whether it will work properly in other IDEs.

This is a program that automatically retrieves video information (Likes, Comments, and more) from Bilibili, one of the largest video platforms in China. I once considered extending the program to support videos from YouTube and TikTok, but I gave up because I couldn’t find valid APIs for them. Therefore, for now, this program can only analyze URLs from Bilibili.

Although BiliBili is a Chinese website, it also has an English version. You can browse it using your browser’s machine translation feature, and there are plenty of English videos available on the platform as well.


HOW TO USE：

This program has no complex requirements. It only needs a computer that can run PyCharm. When you are ready, copy the code into PyCharm and run it.

The Requests library is essential for this program. Please make sure you have it installed. Otherwise, the program will not run. If you are using PyCharm, installing the Requests library is very simple. If you do not know how to install it, just run the program once and when an error message appears, you can follow PyCharm’s prompt to install the library automatically.

Follow the instructions and enter the URLs of the Bilibili videos you want to analyze. Use a comma (remember, no space after that comma) to separate multiple URLs. You can run as many tasks as you want at once. The program will then display information about these videos.

Don’t worry about whether this program can analyze your URL, because the code can handle any video URL that contains a BV number (the BiliBili video identifier). If you enter a correct video link, the link will always include a BV number. The program also includes two error-checking steps: one verifies that the URL you entered is valid, and the other checks whether the video is still available. If an error occurs, the program will show a clear message explaining the reason.

If it runs successfully, you will see the information for the videos you selected.

That's all, hope you like it!
