##翻译步骤指南

####步骤1: 将源码克隆到本地
    git clone git@github.com:hyperledgerchina/fabric_zh_CN.git
    cd fabric_zh_CN
####步骤2: 转换到目标分支
    git checkout v0.6_zh_CN
####步骤3: 翻译前，确保拉取最新的更新
    git pull
####步骤4: 进入待翻译目录
    cd zh_CN
####步骤5: 翻译
    直接翻译文档，不需要建立新文件
####步骤6: 将翻译推送到github
    git add -A
    git commit -a "翻译某某某文档"
    git push
