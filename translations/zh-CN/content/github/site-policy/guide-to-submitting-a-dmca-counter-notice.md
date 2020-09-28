---
title: 提交 DMCA 反对通知的指南
redirect_from:
  - /dmca-counter-notice-how-to/
  - /articles/dmca-counter-notice-how-to/
  - /articles/guide-to-submitting-a-dmca-counter-notice
versions:
  free-pro-team: '*'
---

本指南介绍 GitHub 处理 DMCA 删除请求反通知所需的信息。 如果您对 DMCA 的概念或 GitHub 处理 DMCA 删除请求的方式有更多一般性疑问，请参阅我们的 [DMCA 删除政策](/articles/dmca-takedown-policy)。

如果您认为 DMCA 删除请求误禁了您在 GitHub 上的内容，您有权通过提交反通知来反对删除。 如果您这样做，我们将等待 10-14 天，然后重新启用您的内容，除非版权所有者在此之前对您提起法律诉讼。 下述反通知形式与 DMCA 法规建议的形式一致，您可以登录美国版权局官方网站：<https://www.copyright.gov> 查看该法规。 Copyright Office's official website: <https://www.copyright.gov>.

与所有法律事务一样，就您的具体问题或情况咨询专业人员始终是最好的方式。 我们强烈建议您在采取任何可能影响您权利的行动之前这样做。 本指南不是法律意见，也不应作为法律意见。

### 开始前

***说实话。***DMCA 要求您对自己的反通知宣誓，如有不实会*受到伪证处罚*。 在宣誓声明中故意说谎是一种联邦罪行 。 (*See* [U.S. Code, Title 18, Section 1621](https://www.gpo.gov/fdsys/pkg/USCODE-2011-title18/html/USCODE-2011-title18-partI-chap79-sec1621.htm).) （*请参阅* [美国法典，第 18 章，第 1621 条](https://www.gpo.gov/fdsys/pkg/USCODE-2011-title18/html/USCODE-2011-title18-partI-chap79-sec1621.htm)。） 提交虚假信息还可能导致民事责任，也就是说，可能被诉经济赔偿。

***调查。***提交 DMCA 反通知可能会产生现实的法律后果。 如果投诉方不同意其删除通知有误，他们可自行决定对您提起诉讼以求继续禁用内容。 在提交反通知之前，您应该对删除通知中的指控进行彻底的调查，并在必要时咨询律师。

***You Must Have a Good Reason to Submit a Counter Notice.*** In order to file a counter notice, you must have "a good faith belief that the material was removed or disabled as a result of mistake or misidentification of the material to be removed or disabled." ([U.S. Code, Title 17, Section 512(g)](https://www.copyright.gov/title17/92chap5.html#512).) Whether you decide to explain why you believe there was a mistake is up to you and your lawyer, but you *do* need to identify a mistake before you submit a counter notice. 我们在过去收到的反通知中，列举了一些删除通知中的错误，例如：投诉方没有版权；我有许可；该代码已在允许我使用的开源许可下发布；或投诉方没有考虑这一事实：我的使用受到合理使用原则的保护。 当然，删除通知中可能还有其他缺陷。

***版权法很复杂。***有时，删除通知可能以比较奇怪或间接的方式指控侵权。 版权法很复杂，可能会导致一些意想不到的结果。 在某些情况下，删除通知可能基于您的源代码在进行编译和运行后能够执行的操作，而指控它侵权。 例如：
  - 通知可能声称您的软件用于[规避版权作品的访问控制](https://www.copyright.gov/title17/92chap12.html)。
  - [有时](https://www.copyright.gov/docs/mgm/)，分发软件也可能侵犯版权，假如您诱使最终用户使用软件侵犯受版权保护的作品。
  - 版权投诉还可能基于软件中[非完全复制](https://en.wikipedia.org/wiki/Substantial_similarity)的设计元素，换句话说，有人可能会发出通知，说他们认为您的*设计*与他们的设计太像了。

这些只是体现版权法复杂性的些许示例。 由于在这些类型的案例中，法律有许多微妙之处，还有一些悬而未决的问题，因此，在侵权指控看起来不那么直接的情况下，寻求专业意见尤为重要。

***反通知是法律声明。***我们要求您完整填写反通知的所有字段，因为反通知是一种法律声明——不仅是对我们的声明，也是对投诉方的声明。 如上所述，如果投诉方在收到反通知后，希望继续禁用内容，则他们将需要提起法律诉讼，寻求通过法院命令制止您从事与 GitHub 上的内容相关的侵权活动。 也就是说，您可能会被起诉（并且您在反通知中同意这一点）。

***您的反通知将被公布。***如我们的 [DMCA 删除政策](/articles/dmca-takedown-policy#d-transparency)所述，**在删节个人信息后，**我们将在 <https://github.com/github/dmca> 上发布所有完整、有效的反通知。 另请注意，尽管我们只公开发布经删节的通知，但我们可能会向权利受影响的任何相关方直接提供相关通知的完整未删节版。 如果您担心自己的隐私，可以请律师或其他法律代表替您提交反通知。

***GitHub 不是法官。***除了确定通知是否符合 DMCA 的最低要求外，GitHub 在此过程中几乎不行使酌处权。 当事方（及其律师）应负责评估其投诉的合理性，并注意，此类通知受伪证处罚条款约束。

***其他资源。***如果您需要其他帮助，可以找到许多在线自助资源。 Lumen 有一套内容丰富的[版权](https://www.lumendatabase.org/topics/5)和 [DMCA 安全港](https://www.lumendatabase.org/topics/14)指南。 如果您参与一个开源项目，需要寻求法律意见，您可以联系[软件自由法律中心](https://www.softwarefreedom.org/about/contact/)。 如果您认为自己的案例特别有挑战，像[电子前沿基金会](https://www.eff.org/pages/legal-assistance)这样的非营利组织可能愿意直接提供帮助，或将您推荐给律师。

### 您的反通知必须...

1. **包括以下声明：“我已阅读并理解 GitHub 的《提交 DMCA 反通知指南》。”**如果您的反通知未包括此声明，但其他内容完整，我们不会拒绝处理；但我们知道您尚未阅读这些指南后，可能会要求您先完成这一步。

2. ***标识被禁用的内容及其出现的位置。***被禁用的内容应该已在删除通知中通过 URL 进行了标识。 您只需复制要提出异议的 URL。

3. **提供您的联系信息。**包括您的电子邮件地址、姓名、电话号码和实际地址。

4. ***包括以下声明：“我宣誓，我坚信材料被删除或禁用是因为投诉有误或材料标识错误，如有不实，愿接受伪证处罚 。”***您也可以选择传达您认为存在错误或错误标识的原因。 如果您将反通知视为传递给投诉方的“便条”，您可以利用这个机会，解释为什么他们不应该针对您的反通知采取下一步行动和提起诉讼。 这是在提交反通知时应该与律师合作的另一个原因。

5. ***包括以下声明：“我同意，我地址所在司法区的联邦地方法院具有管辖权（如果在美国，则为 GitHub 所在的加州北区的联邦法院），我将接受提供 DMCA 通知的人或其代理人递送法院传票。”***

6. **提供您的手写或电子签名。**

### 如何提交反通知

得到回复的最快方式是在我们的 {{ site.data.variables.contact.contact_dmca }} 上输入您的信息并回答所有问题。

您也可以发送电子邮件通知到 <copyright@github.com>。 您可以包含附件（如果您愿意），但在邮件正文中也应包含来函的纯文本版本。

如果非要通过实物邮件发送通知，也没问题，但我们接收和回复通知的时间会*大大*延长 - 并且 10-14 天的等待期从我们*收到*您的反通知时开始。 接收纯文本电子邮件通知比接收 PDF 附件或实物邮件要快得多。 如果您仍希望通过邮寄方式发送通知，我们的实际地址是：

```
GitHub, Inc
收件人：DMCA 代理
88 Colin P Kelly Jr St
San Francisco, CA. 94107
```