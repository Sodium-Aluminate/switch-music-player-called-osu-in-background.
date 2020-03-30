这只是一个存档。

# 在后台切歌

## 依赖
[Lazer](https://github.com/ppy/osu/) + `xdotool`

## 前提条件
osu has been already started.

## 使用方法
1. save that file to anywhere, and `chmod +s` it (if your desktop execute this script as other user.)
2. add a shortkey.

## Known bugs
- 会显示一瞬间前台
- osu! 会被最小化(如果你不注释倒数第二行)
  - osu! 会被放在第二个窗口(如果你注释了倒数第二行)

## troubleShooting
- 无法切歌:
  - change the number after "sleep" and try again
  - check F5/F1 works on osu(if not, change script by your own key configuration in osu)

