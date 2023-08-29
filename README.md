# docker_public




# loguru
format: '<green>{time:YYYY-MM-DD HH:mm:ss.SSS}</green> | <level>{level: <8}</level> | <cyan>{name}</cyan>:<cyan>{function}</cyan>:<cyan>{line}</cyan> - <level>{message}</level>'

# git
remove all the branches which are not on remote: git fetch -p && git branch -vv | awk '/: gone]/{print $1}' | xargs git branch -d
