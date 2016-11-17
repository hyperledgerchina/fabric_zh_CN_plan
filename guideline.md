##翻译步骤指南

####步骤1: 将源码克隆到本地
`git clone https://github.com/hyperledgerchina/fabric_zh_CN.git`
####步骤2: 转换到目标分支
`git checkout v0.6_zh_CN`
####步骤3: 翻译前，确保拉取最新的更新
`git pull origin v0.6_zh_CN`
####步骤4: 翻译(目前只翻译zh_CN目录下的文件)
对你要翻译的文件传创建对应的文件,比如要翻译文件release.md则创建文件release_zh.md  
`git add .`  
####步骤5: 将翻译推送到github
`git commit -am "这次提交的简要描述"`  
`git push origin v0.6_zh_CN`
