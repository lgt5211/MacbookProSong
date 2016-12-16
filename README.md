#15年前macbook pro开启充电提示音的方法
#输入如下命令：
#defaults write com.apple.PowerChime ChimeOnAllHardware -bool true; open /System/Library/CoreServices/PowerChime.app &
#取消提示音的命令:
#defaults write com.apple.PowerChime ChimeOnAllHardware -bool false;killall PowerChime
