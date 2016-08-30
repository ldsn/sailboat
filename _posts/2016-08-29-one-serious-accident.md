---
author: ETY001
date: 2016-08-29 23:58:00
layout: post
title: 严重事故后记
categories:
- 工作日志
---
今晚在吃饭的时候，突然收到邮件提醒，打开一看就懵逼了，内容如下：

```
This email is to confirm that the ‘ldsn’ organization has been deleted from GitHub by ‘XXX’.
Your organization’s repositories and content have been deleted from the system.
You can reply directly to this email if you have any questions or feedback, we’d love to hear from you.
```

立刻在QQ上找到XXX询问，确认`organization`真的被删除以后，就在思考如何恢复的问题了。

最终基本会选用两个方法，一个是团队成员从本地找已经clone下来的代码，一个是通过google的快照来恢复。

到目前为止，团队博客和基金会账目已经完全恢复了。

总结下：

这次虽然由团队成员的误操作引发的，但是根本上还是在于`organization`创立之初，我为了找便利，
就把很多人设置为了`owner`权限，这也为这次事故埋下来祸根。

这次事故后，重新创建了一个团队，不在命名为`ldsn`了，更换为`newLDSN`，算是作为一个纪念碑。
另外，权限原则上不再发放`owner`权限，而只是把所有成员创建`repository`和读写权限开了。
这样如果发生误操作也只是影响到某一个`repository`。

---
2016-08-30补充：没想到github的执行效率很高，今天就恢复了organization了，感谢！

这样newLDSN这个组织就真的成为纪念碑了。
