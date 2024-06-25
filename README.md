# 贪吃蛇游戏 (MATLAB App Designer)
贪吃蛇游戏 (MATLAB App Designer)
这个项目使用 MATLAB 的 App Designer 实现了一个简单的贪吃蛇游戏。游戏包含选择蛇的颜色、设置速度和难度以及显示得分等功能。

# 特性
颜色选择: 从多种颜色中选择蛇的颜色，包括绿色、蓝色、黄色、红色、紫色、青色和洋红色。

速度设置: 选择不同的游戏速度，控制蛇的移动速度。

难度设置: 选择不同的游戏难度，控制障碍物的数量。

实时得分: 游戏过程中实时显示当前得分。

# 安装
确保已安装 MATLAB 及其 App Designer 工具箱。
下载项目代码并打开 MATLAB。
# 使用方法
打开 MATLAB 并在命令窗口中输入 appdesigner 以启动 App Designer。
打开项目中的 SnakeGameApp.mlapp 文件。
点击运行按钮 (Run) 以启动应用程序。
使用界面上的控件选择蛇的颜色、设置速度和难度，然后点击“开始游戏”按钮开始游戏。
# 操作说明
使用键盘的箭头键 (↑, ↓, ←, →) 控制蛇的移动方向。
吃掉红色方块（食物）以增加得分和蛇的长度。
避开障碍物和墙壁，否则游戏结束。
# 代码结构
SnakeGameApp.mlapp: 主应用程序文件，包含界面设计和主要逻辑。

initializeGame(): 初始化游戏参数和界面。

generateFood(): 随机生成食物位置。

generateObstacles(): 根据难度生成障碍物位置。

plotSnake(): 绘制蛇的图形。

plotFood(): 绘制食物的图形。

plotObstacles(): 绘制障碍物的图形。

moveSnake(): 控制蛇的移动。

gameLoop(): 游戏主循环，控制游戏进程。

checkCollision(): 检查蛇是否碰撞到障碍物或墙壁。

changeDirection(event): 根据键盘输入改变蛇的方向。

getSnakeColor(): 获取当前选择的蛇颜色。

onSnakeColorChange(): 响应颜色选择的改变并重新绘制蛇。

# 注意事项
确保 MATLAB 版本支持 App Designer。
遇到任何问题，请检查代码中的注释或联系项目维护者。
# 贡献
欢迎提交问题报告和功能建议。如果有兴趣贡献代码，请 fork 本仓库并提交 pull request。

# 许可证
此项目采用 MIT 许可证。

