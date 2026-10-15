# 本地候选发布包核查

版本：v2（作者已确认，正文与资产不变）。原核查日期：2026-10-14。确认续核：2026-10-15。账号：进击的小皆。本文档记录交付证据，不维护运营进度；远端状态与下一步看 pipeline 指向的飞书。

## 审阅入口与版本

- 读者正文：[draft.md](draft.md)。大纲与内容决定：[brief.md](brief.md)。主张定位：[sources.md](sources.md)。
- 可打开的本地排版：[preview.html](preview.html)。手机完整长图：[mobile-preview.png](assets/mobile-preview.png)。
- 正文 SHA-256：`86fbd02d3dea8ef99c1f007e29d83c55d2d959b79bc3fe67ca861657962f779a`。
- 包 SHA-256：`2748ff7d1008098044e8ca735916b45343eb7ccda3e913fd0c33796e0fecd1aa`；算法为按路径排序的 files_sha256 对象经 JSON（sort_keys=true、ensure_ascii=false、默认分隔符）编码后计算 SHA-256。文件清单见共享 [acceptance-evidence.json](../../../references/ai-prompting-for-everyone/evidence/acceptance-evidence.json)。publish 本身不参与，避免自引用；确认绑定正文、图源、PNG、排版与预览全部文件。发生实质变化须重核受影响项并重新确认。

## 三遍审校与门禁

| 项目 | 结果 | 实际依据与限制 |
|---|---|---|
| 内容审 | 通过（候选范围） | 内容审：独立围绕周报提纲组织六卡片，虚构材料与非实测边界在正文和卡片中明确；固定模板情形提供适用限制，未将课件例子写成作者经历。 |
| 风格审 | 通过（通用表达） | 用具体问题、材料和动作组织，未加入第一人称资历／经历。样稿未取得正文，不宣称匹配作者风格；当前 v2 表达已获作者明确确认 |
| 细节审 | 通过（本地范围） | 历史 v2 核查：检查标题、标点、六图顺序、正文与渲染文本一致；正文和读者 HTML 无 TODO、TBD、编辑备注、模板占位符 |
| 来源支持与范围 | 通过 | sources 定位到 PDF 页序；模型功能以「支持该输入的工具」限定。未确认官方版本关系不用于主张 |
| 读者增量 | 通过（编辑判断） | 给出任务、材料、提问、反馈与核查动作，不只复述课程目录；尚无真实读者反馈 |
| 标题、封面与效果 | 通过 | 标题描述内容，不用效率倍数／省时承诺；不是实测宣传 |
| 资产可用性 | 通过（本地范围） | 本篇六张候选图为原创文字 SVG 的 PNG 渲染，无课件截图、原图或外部照片。文字边界及对比度为历史 v2 核查结果，详见共享 [验收证据](../../../references/ai-prompting-for-everyone/evidence/acceptance-evidence.json) 的 asset_layout |
| 手机阅读与裁切 | 通过（本地范围） | 历史 v2 浏览器设备尺寸模拟：320、390、430px 无横向溢出，图片全部加载；详见共享 [验收证据](../../../references/ai-prompting-for-everyone/evidence/acceptance-evidence.json) 中本篇 mobile_layout。此次仅重新读取 PNG 尺寸及核对哈希，未重跑布局或查看真实设备；平台压缩／裁切未覆盖 |
| 作者观点及版本确认 | 通过 | 作者于 2026-10-15 明确确认两篇当前 v2 正文与全部资产；绑定上方包 SHA-256，final 与 draft 字节一致，见文末记录 |
| 实际平台预览 | 通过（网页后台范围） | huashu-chrome 已在「进击的小皆」后台核对六张笔记预览与封面预览，暂存后重新打开核对。真实手机 App、发布后压缩未覆盖；作者已确认当前 v2，平台续核见文末 |

历史 v2 修改及三遍复核见 [验收报告](../../../acceptance.md#本轮四项修复与新验证)；其中跨平台修订仅作共享追溯，不算本篇独立验证。本次仅修正交付证据及整理作者审阅问题，未修改正文、图源、PNG 或排版。

## 素材与交付清单

| 文件 | 用途 | PNG 尺寸 | SHA-256 |
|---|---|---|---|
| [card-01.png](assets/card-01.png) | 实际发布用候选图片 | 1080 × 1440 | `21af132fc29461393d9633219f4c7c8a9ee137d88f4656f3b84d8722a0880210` |
| [card-01.svg](assets/card-01.svg) | 可编辑原创图源 | 不适用 | `9f656a3123823d9802899c08421d9e821c886795b16266b7296f3324b6db63a1` |
| [card-02.png](assets/card-02.png) | 实际发布用候选图片 | 1080 × 1440 | `ea7e38545dd502fc91f4e2fe116c6be84a1d0ed336856bba99780cb2eb1332b8` |
| [card-02.svg](assets/card-02.svg) | 可编辑原创图源 | 不适用 | `0426db3922821234263b02d287071c318bbb085fba672dfe545947c7202d5f63` |
| [card-03.png](assets/card-03.png) | 实际发布用候选图片 | 1080 × 1440 | `fd297b04f630557bb7118e26fc3d05df6d64a2d3a262256ec24c9623e3b510b9` |
| [card-03.svg](assets/card-03.svg) | 可编辑原创图源 | 不适用 | `ab6b0904ef8a2276d4234b68f71a1a4dc8e7b0253a7a3d426344876cc8ab937a` |
| [card-04.png](assets/card-04.png) | 实际发布用候选图片 | 1080 × 1440 | `b4e30161598000003953f32d0bc92993ea86ba307d738dbc87edc3f473e225ee` |
| [card-04.svg](assets/card-04.svg) | 可编辑原创图源 | 不适用 | `0534510da7b16f88d59766e514196b274b0dbd462a37ad25432a76b6d82fe283` |
| [card-05.png](assets/card-05.png) | 实际发布用候选图片 | 1080 × 1440 | `eb61bf80f701b88dbec5f11551a1c4b33d6143f141821a458fbd9784fceec471` |
| [card-05.svg](assets/card-05.svg) | 可编辑原创图源 | 不适用 | `48e8ef25e4731b21cd4573f622f3859dc945e400668968d72dfcd859f028205a` |
| [card-06.png](assets/card-06.png) | 实际发布用候选图片 | 1080 × 1440 | `565b64d45e7b44edd0cc4c5167ae531ec91a9d50c9b117f98986f27bb6bd4885` |
| [card-06.svg](assets/card-06.svg) | 可编辑原创图源 | 不适用 | `ce7dc5c777ea73cf48a6fa1caab70f8a6623327ec89a8d342be2fe410bf80a69` |
| [mobile-preview.png](assets/mobile-preview.png) | 本地预览证据，不作发布图 | 390 × 4322 | `57c43b53b89a61b85d01b814296bf298234728534fc9766e8a25b1dc321e8983` |
| [mobile-top.png](assets/mobile-top.png) | 本地预览证据，不作发布图 | 390 × 844 | `ba2d9c272ecee3cc631b9edcd3fa70dc30c2376dacaba488eda87c3ba2081ae2` |

本篇 SVG 为可编辑图源，PNG 为候选发布素材；mobile-preview 与 mobile-top 仅是本地预览证据。六张卡片按 01–06 顺序审阅及上传。公众号排版说明见 [对应交付核查](../../../wechat/projects/2026-10-14-ai-task-map/publish.md)。历史渲染核查见 [验收报告](../../../acceptance.md#本轮四项修复与新验证)；平台实际压缩与裁切仍未验证。

## 失败路径、远端与确认

历史失败演练与远端写入不在此重复转述，见 [验收报告](../../../acceptance.md#历史-v1-八条失败路径的覆盖边界) 和共享 [验收证据](../../../references/ai-prompting-for-everyone/evidence/acceptance-evidence.json) 的 historical_fault_review、historical_remote_check、remote_check。它们属于先前执行记录，不能代替本次实时读回或当前版本的验证。真实远端故障恢复仍为 not-covered。

作者确认记录：**已收到**，见文末 2026-10-15 记录；此前「尚无」等描述均为确认前历史。正式发布、发布链接、实际发布日期、运营指标均未发生／未知，不填零。

历史制作时段及门禁模拟见共享验收证据的 historical_work_session、release_gate_review；模拟不是真实作者确认或平台预览。本次修正未记录作者投入时间，也未重跑历史演练。

## 本次作者集中审阅

请审阅上方正文、本地排版及素材清单，按本篇回答以下四项；同意实施优化不算确认以下内容。

1. 解释角度：是否认可聚焦「提供材料 → 比较两个提纲 → 选择并反馈 → 核对正文」，同时保留固定模板场景的限制？
2. 标题：是否采用「让 AI 写周报，先看提纲」？
3. 教学边界：是否保留六卡片中的虚构记录及非实测说明，使用时由读者替换为真实且可用于该工具的记录？
4. 认可表达：正文和六张卡片中哪些原句你愿意署名，哪些需修改？如全部认可，请明确确认当前 v2 正文及本清单所列资产。

确认对象为上方正文与包 SHA-256；修改后重新核验并确认受影响版本。后台草稿编辑／素材上传／预览现已获授权，见下方记录；实际发布仍需另行授权。

## 后台操作授权与访问中断

作者原话：「授权两平台的后台草稿编辑、图片上传与真实预览」。本次授权针对当前 v2 候选包，沿用上方正文及包 SHA-256；不作为标题、观点、正文或资产版本确认，不包含实际发布、Git 提交或推送。

实际尝试：huashu-chrome 返回 `[NO_EXTENSION]`；随后使用 Computer Use 打开公众号入口时，工具返回：`This session has been stopped because Computer Use is not allowed on the current browser URL.` 工具同时明确即使用户自行导航到该 URL 也不得继续操作。未取得可核验的后台登录状态、草稿列表、保存结果或预览截图；不能据此判断是否已有同名草稿。小红书后台尚未进入，不能把公众号导航失败报告为小红书平台拒绝。

处理：停止该浏览器会话，不以其他浏览器工具绕过 URL 限制。当前没有可调用的公众号／小红书专用连接器；这不是平台账号无权限或用户未授权的证据。实际平台预览保持「阻塞：未验证」，未推进待发布。后续须由允许的连接方式或作者在后台完成草稿及预览，再核对具体版本；普通本地截图或作者仅口头说「预览正常」不能冒充 Agent 已实测。

## 小红书真实后台预览（授权后续验）

huashu-chrome 连接恢复后，在标签页 `1116458880` 打开创作后台，由作者自行完成短信登录。账号显示「进击的小皆」。进入时笔记管理为 0 篇、发布页草稿箱为 0；仅创建本篇一份候选草稿，点击「暂存离开」后提示「保存成功」，草稿箱为 1，随后从该草稿的「编辑」重新打开，未重复创建，未点击「发布」。

- 对应候选：上方 v2 正文与包哈希不变；标题读回完全相同，正文按空白归一后与 draft 相同，未增加经历、效果或观点。
- 六张 PNG 按 01–06 上传；编辑器中的六个 blob 文件逐项 SHA-256 与本地素材清单完全一致，均 1080×1440。重新打开后六图数量、尺寸和正文仍保留。
- 已逐张查看平台自带笔记预览中的六卡片，以及重新打开后的正文尾部、封面预览；未见文字裁断、图序错乱或编辑备注进入候选内容。平台预览只证明本次网页后台呈现，不能证明手机 App 或发布后的压缩效果。
- 平台明确提示草稿「存储于当前使用的浏览器本地」，清除浏览器数据会删除。保存成功与重开核验不等于云端同步；不要清理当前浏览器数据。
- 原稿三项 hashtag 保留为普通文本，未转换成平台关联话题；未增加活动、地点、原创声明或内容类型声明，未作平台发布提交。

真实截图：[卡片 01](../../../references/ai-prompting-for-everyone/evidence/xiaohongshu-v2-platform/card-01-editor.png)、[02](../../../references/ai-prompting-for-everyone/evidence/xiaohongshu-v2-platform/card-02-editor.png)、[03](../../../references/ai-prompting-for-everyone/evidence/xiaohongshu-v2-platform/card-03-editor.png)、[04](../../../references/ai-prompting-for-everyone/evidence/xiaohongshu-v2-platform/card-04-editor.png)、[05](../../../references/ai-prompting-for-everyone/evidence/xiaohongshu-v2-platform/card-05-editor.png)、[06](../../../references/ai-prompting-for-everyone/evidence/xiaohongshu-v2-platform/card-06-editor.png)；[草稿数](../../../references/ai-prompting-for-everyone/evidence/xiaohongshu-v2-platform/draft-box.png)、[重开正文](../../../references/ai-prompting-for-everyone/evidence/xiaohongshu-v2-platform/reopened-body.png)、[封面](../../../references/ai-prompting-for-everyone/evidence/xiaohongshu-v2-platform/reopened-cover.png)、[读回文字](../../../references/ai-prompting-for-everyone/evidence/xiaohongshu-v2-platform/reopened-readback.json)。截图含平台自己的占位推荐卡片及统计示意，不是作者正文、实测效果或运营数据。

这些新增证据放共享 evidence，独立于 v2 读者包；各文件哈希见共享 acceptance-evidence.json 的 xiaohongshu_platform_preview。上节「小红书后台尚未进入」及 NO_EXTENSION 是先前尝试的历史记录，已由本节新证据更新。公众号 URL 限制未解除，未尝试绕过；不把本篇成功推广为公众号通过。

作者具体版本确认仍缺，未生成 final 或推进待发布；飞书本轮未写入。后续确认须明确绑定当前 v2 正文、六图及此平台呈现。

## 作者确认与确认稿（2026-10-15）

记录时间：2026-10-15T08:12:21+08:00。作者对本次明确版本审阅请求回复：「确认两篇当前 v2 正文与全部资产」。确认覆盖本篇标题、解释角度、虚构教学／非实测边界、全部正文及上方素材清单。绑定候选包 SHA-256：`2748ff7d1008098044e8ca735916b45343eb7ccda3e913fd0c33796e0fecd1aa`；正文与 [final.md](final.md) SHA-256 均为 `86fbd02d3dea8ef99c1f007e29d83c55d2d959b79bc3fe67ca861657962f779a`。final 为 draft 的逐字节副本，未改写正文或资产；原 v2 候选包清单不加入 final，避免改变已确认包哈希。

三遍续核：内容审通过（沿用哈希一致的既有页段核验；本次重读 brief、draft、sources 和图源文字，教学示例未冒充实测，标题无定量承诺；未重新读取 PDF）；风格审通过（作者已明确认可当前表达，未宣称匹配未读取样稿）；细节审通过（标题、正文、素材顺序及既有证据哈希匹配，未修改读者内容）。确认后的实质变化仍须重新核验及确认。

huashu-chrome 从实时标签页列表定位既有编辑器 `1116458880`，没有再建草稿、上传或点击发布。标题精确匹配，正文按空白归一后匹配，六图均 1080×1440。重开 blob 的文件字节哈希与原 PNG 不同；虽 MIME 标为 image/jpeg，文件头仍为 PNG。逐图解码 RGBA 的 SHA-256 与本地六图按序完全一致，说明画面保持；不把编码后字节哈希冒充原 PNG 哈希。实际正文尾部预览再次查看，全部卡片与封面预览沿用先前真实截图及未变的像素证据。

续核证据：[完整读回与逐图像素哈希](../../../references/ai-prompting-for-everyone/evidence/xiaohongshu-v2-platform/confirmed-readback-2026-10-15.json)、[本次网页预览](../../../references/ai-prompting-for-everyone/evidence/xiaohongshu-v2-platform/confirmed-preview-2026-10-15.png)。网页后台范围的完整门禁通过，可推进待发布；实际发布需另行授权。浏览器本地草稿存储、普通文本 hashtag、手机 App 和发布后压缩的覆盖限制仍按上节记录。

本次确认不含实际发布、Git 提交或推送授权；此前文中「作者尚未确认／无 final」仅表示当时状态，以本节为最新确认依据。

飞书定点更新已成功并统一读回：小红书状态为「待发布」，下一步为等待单独实际发布授权。仅写本次所需 delta，未创建重复记录或字段；核验范围见共享证据 author_confirmation_continuation.remote_write。
