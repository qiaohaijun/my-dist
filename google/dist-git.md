前两天看到了谷歌的一个分布式git的产品。

http://www.infoq.com/cn/news/2016/02/google-kick-starts-git-ketch?utm_campaign=rightbar_v2&utm_source=infoq&utm_medium=news_link&utm_content=link_text

---

为什么需要个分布式的git

---

这个问题其实很简单，为了不让宝贵的代码化作乌有。

---

这个问题其实前两天和小伙伴们吃饭的时候聊到了一个gitlab服务挂了的事情，服务器挂了其实很正常的，哪有不挂的服务器。

问题就在这儿，作为一个为很多人服务的gitlab,你就不能挂。



我还没有看到这个服务的架构，但是觉得，这个服务应该类似paxos

raft也可能用到

---

当然应该是做了某种的折中，速度慢的git服务器，我也不用


---
### 基本单元
jgit 我查了一下，jgit是eclispe的项目
