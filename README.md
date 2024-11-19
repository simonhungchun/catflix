1. 移动 master 指针
   git reset --hard HEAD^^
   git reset --hard commitID
   git reset --hard HEAD 放弃工作区和暂存区的修改
   【什么时候使用回退命令】
   1.1 当你提交的代码中存在一些小问题 那么可以使用软回退（git reset --soft 目标）/混合回退（git reset --mixed 目标）
   1.2 当你提交的代码 整体上都不需要的时候 那么可以使用硬回退（git reset --hard 目标）
