# 2024-10-17-demo-repo
A repository for the RStduo git workshop
# generate token using "usethis"package
> install.packages("usethis")
> library(usethis)
> usethis::use_git_config(user.name="fuhailu0416", user.email="fuhailu0416@gmail.com")
#pop up a window in github to let you set your token
> usethis::create_github_token()
#ask you to enter your token
>> gitcreds::gitcreds_set()