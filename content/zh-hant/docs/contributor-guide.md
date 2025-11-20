---
title: 貢獻者指南
---

## 貢獻方式：

1. 會 GitHub 操作，直接 PR 或者 透過 {{< shields/github-issue "project-trans/mtf-wiki" >}}
2. 傳送郵件到 <mtfwiki@project-trans.org>
3. 直接在每个页面下方的意见反馈中投递

## 基本原则 {#basic-principle}

1. 绝对不要做出任何 {{< wiki 道德绑架 >}} 的行为
2. 为了保证内容的 {{< wiki 客观性 >}}，因此不受理虚构内容
3. 不应存在显著的 {{< wiki 谬误 >}}，亦可对照 {{< wiki 谬误列表 >}} 进行检查
4. 不应存在明显的 {{< wiki 认知偏差 >}}，亦可对照 {{< wiki 认知偏差列表 >}} 进行检查
5. 使用 [性别包容性语言][inclusive-language] 描述避免触发读者的 性别焦虑
6. 对于“缺乏真实案例报告”的内容，应当创建 [issue][new-issue] 后并记录至 \[未确认列表]\({{< ref "unconfirmed" >}})

[new-issue]: https://github.com/project-trans/MtF-wiki/issues/new/choose
[inclusive-language]: https://www.un.org/zh/gender-inclusive-language/guidelines.shtml

## HRT/診斷證明 {#proof}

### 友情提醒

1. 医生对开证有清晰的条件，医生本人知晓开证是在干什么。医生了解诊断证明乃手术条件之一，知晓开证可能会被家长闹事。
2. SRS {#srs}
3. 明确只有能开诊断证明的精神科才有收录的必要。
4. 对于 HRT 医生，医生知晓自己在给跨性别者提供激素治疗，而不是顺手开药（点菜）。

### 撰稿要素

1. 醫生姓名
2. 所在醫院
3. 出診時刻
4. 掛號方法
5. 問診細節
6. 注意事項

### 撰稿原則

1. 您對於醫生的印象/屬性 tag（如：「一次過」、「可與家長溝通」 等）可能不會第一時間更新在醫生頁面上，我們需要進行多方求證（來自不同來源/時期的報告）。
2. 對於需要標註 「跨性別友好」 的醫生，我們需要進行多方求證（來自不同來源/時期的報告）。
3. 在编写内容时请尽量不要包含强时效性（可能短期内过期）或存在特殊情况的内容，比如周更的出诊时间表，这种情况可以给出获取最新信息的方式。\
   如果你觉得自己提及了一些强时效性的内容，且是必要的，可以在上标中标注时间（如：我可以吞下玻璃而不伤身体<sup>2023-03-31</sup>）。
4. 問診細節原則上需要清晰、明確的表述，如果對方願意開具比較詳細的病歷請務必要求開具相關病歷。並且可隨醫生資訊一同上傳其開具的病歷（圖片）以供參考。
5. 由於科室不同，開具診斷證明的醫生沒有權利開具 HRT 處方，開具 HRT 處方的醫生沒有權利開具診斷證明，這是基本常識。望貢獻者在撰寫醫生介紹的時候切記。
6. 假如某位醫生資訊被編入 wiki 後表示自己不願意被公開資訊，我們將遵從其主觀意願將有關詞條刪除並列入過時名單。

## 報告新的 SRS 醫生

1. 醫生姓名
2. 所在醫院
3. 如何預約
4. 手術前置要求
5. 手術技術（醫生描述，第三方介紹，發表論文）
6. 有無例項（如醫生提供近期案例，朋友、自己接受手術）

### 手術評價、術後效果

見：[手術評價方法]({{< ref "srs-compraise" >}})

## 关于附加资源

### 图片处理

如果該圖片為對紙質材料的拍攝請使用 Microsoft Lens (fbk Office Lens) 進行掃描以便於提供更好的閱讀體驗
當然如果有條件的話建議提供掃描件，如果您不會相關的後處理（可以將該圖片提交至 <mtfwiki@project-trans.org> 由我們進行脫敏後進行上傳）
照片中的 {{< wiki Exif >}} 信息可能包含设备型号、拍摄时间和地理位置等信息。建议您在上传前[移除敏感信息](https://commons.wikimedia.org/wiki/Commons:Exif#Editing_Exif_fields)。
如果您不会相关的后处理，可以将该图片提交至 <mtfwiki@project-trans.org> 由我们脱敏后进行上传。

[Microsoft Lens (Android)](https://play.google.com/store/apps/details?id=com.microsoft.office.officelens)
[Microsoft Lens (iOS)](https://apps.apple.com/app/id975925059)
[Microsoft Lens (Windows)](https://www.microsoft.com/en-us/p/office-lens/9wzdncrfj3t8)

### 附件目录

根据规范，不同种类附件都有存放目录，建议将附件存放至规范的目录下。

- 图片类附件建议建议存放至 [`/static/images/`][images] 目录下，在正文中使用 `/images/+路径` 的方式引用；
- PDF 等文档类附件建议存放至 [`/static/documents/`][documents] 目录下，在正文中使用 `/documents/+路径` 的方式引用；

[images]: https://github.com/project-trans/MtF-wiki/tree/master/static/images/
[documents]: https://github.com/project-trans/MtF-wiki/tree/master/static/documents/

### 表格

表格类说明建议使用内嵌 {{< wiki CSV >}} 格式

<!-- markdownlint-disable-next-line -->

````
```csv
表头1,表头2,表头3
内容,内容,内容
```
````
