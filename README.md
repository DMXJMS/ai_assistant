<!--
 * @Author: kraken8081 202024@cumtb.edu.cn
 * @Date: 2024-08-05 14:37:59
 * @LastEditors: kraken8081 202024@cumtb.edu.cn
 * @LastEditTime: 2024-08-13 11:22:30
 * @FilePath: /GitHub/ai_assistant/README.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
# 端到端语音交互AI法律助手
- ## 环境安装


    python版本：Python 3.8.19
    ```shell
    conda create -n ai_assistant python=3.8 -y

    pip install -r requirements.txt 

    # 安装ollama，以Linux系统为例
    # 其他系统安装请参考 https://github.com/ollama/ollama/tree/main
    curl -fsSL https://ollama.com/install.sh | sh
    # 启动ollama服务
    ollama serve

    # 下载llm模型
    ollama pull qwen:0.5B

    # 下载cosyvoice和sensevoice对应模型到 pretrained_models
    # 可使用download.ipynb

    # 启动服务
    python main.py
    

    ```

