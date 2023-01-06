# CONTRIBUTING

这里是 HUSTACM GitHub Organization 贡献指南，如果你有任何的建议、提案，抑或者你是 HUSTACM 集训队一员，并且希望在你的 GitHub 账号上添加 HUSTACM 组织标识，请参见以下文章进行贡献，**一旦你的 PR 被允许合并**，我们将会邀请您成为我们组织的成员。

我们希望这个组织能够继续发展壮大，并且有人能够持续维护该组织的项目，我们非常需要你的支持。继任队长若有需要域名、邮箱、GitHub 组织等服务，请联系现任维护者：[i@ligen131.com](mailto:i@ligen131.com)。

## Join HUSTACM Organization

如果你还不熟悉 GitHub 各种基本操作，请自行根据下列名词在搜索引擎中搜索。

**请注意：不符合规范的提交将不会被合并。**

1. Fork [仓库 hustacm.com](https://github.com/HUSTACM/hustacm.com)。
2. 在本地 Clone 你 Fork 之后的仓库：
   
   ```shell
   $ git clone https://github.com/【替换为你的 GitHub ID】/hustacm.com.git
   ```

3. 在仓库路径：`hustacm.com/docs/avatar/` 文件夹下放置**用你的 GitHub ID 命名的**头像文件，头像文件要求：
   
   - 必须为正方形，即长宽相等。
   - 文件格式为 `.jpg/.jpeg/.png/.webp/.bmp`，如果你的头像文件非以上文件格式，请自行转换后再提交。
   - 图片大小不小于 200×200，文件大小不大于 2 MB。
   - 尽量使用你在 GitHub 中使用的头像。

4. 在仓库路径：`hustacm.com/docs/Contributor.md` 下 `Member` 章节，仿照之前内容格式，在最后一个 `</td>` 和 `</tr>` 之间换行并添加如下内容（请根据你的实际情况替换 `【】` 及之间的内容）：
   
   ```html
      <td align="center">
        <a href="【你的个人网站网址，请加上 http 或 https，若无请填写 GitHub 主页地址】">
          <img src="/avatar/【你在 avatar 路径下放置的头像文件名】" width="100px;" alt="【你的 GitHub ID】"/>
          <br />
          <sub><b>【你的 GitHub ID】</b></sub>
        </a>
        <br />
        【你的一句话介绍、座右铭等，请不要过长】
        <br />
        <a href="【你的个人网站网址，请加上 http 或 https，若无请直接删除该 <a> 字段】" title="Personal Website">🌐</a>
        <a href="mailto:【你的电子邮箱】" title="E-mail">📧</a>
        <a href="【你的 GitHub 个人主页地址，请加上 https】" title="GitHub">💻</a>
        <a href="【你的 Codeforces 个人主页地址，请加上 https，若无请直接删除该 <a> 字段】" title="Codeforces">🏅</a>
      </td>
   ```

   以下是一个符合规范的例子：

   ```html
      <td align="center">
        <a href="https://ligen131.com">
          <img src="/avatar/ligen131.png" width="100px;" alt="ligen131"/>
          <br />
          <sub><b>ligen131</b></sub>
        </a>
        <br />
        Don't worry, be happy.
        <br />
        <a href="https://ligen131.com" title="Personal Website">🌐</a>
        <a href="mailto:i@ligen131.com" title="E-mail">📧</a>
        <a href="https://github.com/ligen131" title="GitHub">💻</a>
        <a href="https://codeforces.com/profile/1353055672" title="Codeforces">🏅</a>
      </td>
   ```

   请遵守对应页面的缩进，上下 HTML 代码之间**请勿存在任何空行**。

   一旦你的提交被通过，你可以在 <https://hustacm.com/Contributor/> 看到效果。

5. 修改完成后请遵守 Commit 规范，你可以直接使用以下命令进行 Commit：

   ```shell
   $ git add .
   $ git commit -m ":sparkles: New member: 【你的 GitHub ID】"
   $ git push
   ```

6. 在 [hustacm.com 仓库](https://github.com/HUSTACM/hustacm.com)下提交 Pull Request，并与你 Fork 后的仓库进行比较，提交之后，等待管理员审核与合并。

一旦你的 Pull Request 被合并，我们将会邀请你加入 HUSTACM GitHub Organization。

## 提出 ISSUE

如果你有任何形式的建议或提案，欢迎随时在对应项目下提请 ISSUE。

We sincerely thank everyone who has contributed to this organization.
