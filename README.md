**Blank Repl**

```bash
git clone https://github.com/gopcn/cloudreve.git \
&& shopt -s dotglob \
&& mv -b cloudreve-replit/* . \
&& rm -rf *~ cloudreve-replit .git README.md .github \
&& echo "部署成功，点击Run使用。"
```
