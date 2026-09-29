# 2026 秋季公路旅行游记

这是一次秋季公路旅行的旅行记录（游记）。旅程从 Silicon Valley 出发，经 Vancouver 横跨加拿大前往 Halifax，之后返回美国并驶回西海岸。

本项目同时是一个 Obsidian Vault。旅行路线、每天实际发生的事情、餐饮体验、住宿情况和沿途决定都会持续记录在这里。

## 文件结构

```text
Travel_Plan.md
Travel_Journal/
  Day_XX_Place_Name/
    funs_of_day.md
    hotel_info.md
Media/
  Day_XX_Place_Name/
    Photos/
    Videos/
```

### `Travel_Plan.md`

记录整趟旅行的路线框架、每日索引、固定预约、安全和住宿原则，以及尚未完成的后续大环线计划。

### `funs_of_day.md`

每个 Day 目录中的 `funs_of_day.md` 是当天的主要游记，记录：

- 当天实际行驶的路线和做过的事情
- 参观的景点与途中停留
- 吃饭的餐厅、食物和用餐体验
- 当天的天气与路况
- 临时改变的计划和重要决定
- 前一天、下一天和总计划的 Obsidian 链接

文件中的“候选地点”或“建议”应明确标注，不应与实际完成的行程混在一起。

### `hotel_info.md`

每个 Day 目录中的 `hotel_info.md` 记录当天的住宿情况，包括：

- 实际入住的酒店名称和城市
- 入住日期、房型和价格
- 停车、早餐和 Wi-Fi 情况
- 是否安静、有工作空间，以及是否适合交易
- 取消政策或其他住宿备注

尚未确认的信息标记为“待补充”。预订确认编号只应在仓库为私有且确认安全时记录，任何情况下都不要保存付款卡信息。

## 照片和视频

照片与视频统一放在 Vault 根目录的 `Media/` 中，并使用与游记相同的 Day 目录名：

```text
Media/
  Day_01_Ukiah/
    Photos/
    Videos/
  Day_02_Crescent_City/
    Photos/
    Videos/
```

### 媒体文件命名

媒体文件名使用英文、日期和简短说明，不使用空格。例如：

```text
2026-09-10_city_of_ten_thousand_buddhas_01.jpg
2026-09-10_redwood_drive_01.mov
```

### 在当天游记中嵌入照片

在对应的 `funs_of_day.md` 中使用 Obsidian 嵌入语法：

```md
![[Media/Day_02_Crescent_City/Photos/2026-09-10_city_of_ten_thousand_buddhas_01.jpg]]
```

也可以附加图片说明：

```md
## 当日照片

### City of Ten Thousand Buddhas

![[Media/Day_02_Crescent_City/Photos/2026-09-10_city_of_ten_thousand_buddhas_01.jpg]]

早上离开 Ukiah 后参观 City of Ten Thousand Buddhas。
```

视频可用相同方式嵌入：

```md
![[Media/Day_02_Crescent_City/Videos/2026-09-10_redwood_drive_01.mov]]
```

### GitHub 注意事项

- 普通照片适合直接提交到 GitHub，但建议保留合理尺寸并删除不需要的重复照片。
- 大型视频很容易超过 GitHub 的单文件限制，建议使用 Git LFS，或把视频上传到私人云盘后在游记中记录链接。
- 照片可能包含拍摄地点、时间和设备等 EXIF 信息；公开仓库提交前应检查是否需要删除这些隐私信息。

## 记录规则

- Markdown 文件名使用英文，单词之间用下划线连接，不使用空格。
- 正文以中文记录；地点名、人名、酒店名和餐厅名保留原文。
- 日期统一使用 `YYYY-MM-DD` 格式。
- 已经发生的事情与计划、建议或候选项目必须明确区分。
- 使用 Obsidian wikilinks 连接每日游记、酒店信息和 `Travel_Plan.md`。
