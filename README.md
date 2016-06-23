# HelloTest
今天重装了AS，但是在运行项目的时候遇到了这个问题，Error type 3 Error: Activity class {} does not exist
然后在网上搜了一下，全是英文的的解答，本来不愿看的，没想到最后竟然是在这些英文答案里知道了解决方案！非常意外也很惊喜！
解决方案是：Open Run->Edit Configuration, check if "Deploy default APK" is chosen in the package panel. "Deploy default APK" should be chosen.

The problem occurs to me because I choose "Do not deploy anything" earlier for some reason and I forget to undo the chosen.
