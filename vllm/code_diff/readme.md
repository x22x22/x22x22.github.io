本目录存放的是当前分支的代码和mian分支对比后的代码改动点输出。执行命令如下：

git diff main -- vllm/config.py > diff_config.py.txt
git diff main -- vllm/entrypoints/openai/serving_embedding.py > diff_serving_embedding.py.txt