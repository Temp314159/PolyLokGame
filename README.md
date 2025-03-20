# CompactPuzzleGame
## 简介
一个基于Pygame的数学拼图游戏，目标是创建若干骨牌拼图并拼成可以紧密移动而不散开的结构。

## 游玩方法
在Releases中下载压缩包，其中有构建好的Windows可执行程序。

macOS和Linux需要手动打包或在Python环境下运行.py脚本。

## 玩法规则
### 基本操作
- 左键点击或者按住拖动，选中格子；右键点击或者按住拖动，清空选中的格子。
- 点击 create 或按下 Enter / 空格，根据选中的格子创建拼图块。
- 左键点击选择拼图块，按住拖动移动拼图块，点击 delete 删除拼图块。
- 将拼图块拼成目标结构后，点击 complete 或按下 C 键，完成拼图，进入结算环节。
### 其他操作
- 点击 restart 或按下 R 键清空盘面。
- 点击 undo 或按下 Z 键撤销一步。
- 按住鼠标中键并拖动，移动盘面。
- 拖动滑动条、按下 +/- 按钮、按下 +/- 键，或滚动鼠标滚轮，缩放盘面。
### 游戏目标
- 保证最终的拼图结构无论如何移动，都不会散开（每一块拼图块的相对位置都不改变）。
- 在此基础上，追求更高的分数。目标是：减小 最大拼图块的格子数、总格子数，并在减小到一定的情况下，增大 拼图块数量、最大拼图块的格子数与总格子数的比例，并避免过于简单的结构（如全包围）。

## 更新计划
- [x] 成功时计算分数
- [x] 添加音效
- [ ] 增加成功/失败的炫酷动画
- [ ] 支持窗口缩放与全屏模式（当前存在渲染bug）
- [ ] 分数算法优化

## 碎碎念
为了智力题活动写的游戏，未来将移植到前端。目前后端程序跑路失联了，活动未来可期。
