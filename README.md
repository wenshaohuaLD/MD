# MD
The data is available.
1
# 跳转到 https://github.com/settings/tokens，创建Token
usethis::create_github_token()
# 粘贴保存创建的Token
2
# 查看
3


usethis::git_remotes()
# 查看远程库和地址
usethis::git_remotes()
# 修改远程库和地址
usethis::use_git_remote(
  "MD",
  "https://github.com/wenshaohuaLD/MD.git",
  overwrite = TRUE
)


ssh-keygen -t rsa -b 4096 -C "Rstudio"
# ssh-keygen -t ed25519 -C "Rstudio"


credentials::set_github_pat()

usethis::gh_token_help()

usethis::git_sitrep()

gh::gh_whoami()

