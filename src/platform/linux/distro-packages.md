# 各 Linux 发行版分发的软件包

> 原
> 文：[Linux Distro Packages - Anki Manual (ankiweb.net)](https://docs.ankiweb.net/platform/linux/distro-packages.html)

我们发现，由 Linux 发行版分发的 Anki 自定义版本导致了许多问题：

- Anki 依赖于像 Qt 这样的第三方库，Linux 发行版经常在未测试这些更改影响的情况下替换不同版本的这些
  库。
- 有时，他们分发的 Anki 版本是多年前的版本，或者是并不适合稳定发行的 alpha/beta 版本。发行版通常也会
  禁用内置的更新检查，以防止你收到新版本的通知。

在 <https://apps.ankiweb.net> 可下载到 Anki 的已编译构建版本。大多数必要的库都已包含其中，并且 Anki
已经过测试可以与这些版本的库一起正常使用。如果你在使用发行版的版本时遇到问题，你应该首先尝试切换到我
们提供的最新打包版本。

如果你愿意，当然可以继续使用发行版的 Anki 版本。但如果遇到任何问题，你需要向发行版的软件包维护人员报
告。
