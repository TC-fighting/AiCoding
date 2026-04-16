添加readMe的内容
1、git commit -m "fix: bug修改" -m "Co-authored-by: Claude <noreply@anthropic.com>"

2、# AI 写的代码，用 --author 指定 tc-ai 账号
git commit --author="tc-ai <tc-ai的邮箱>" -m "feat: AI生成的功能"

3、每次手打 --author 太麻烦，可以设置别名：

git config --global alias.ai-commit '!git commit --author="tc-ai <tc-ai的邮箱>"'

4、 # 人工提交
git commit -m "feat: 人工功能"

# AI 提交（一个命令搞定）
git ai-commit -m "feat: AI生成的功能"