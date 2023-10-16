# Code Llama

> GitHub: https://github.com/facebookresearch/codellama

## 下载模型

### 申请

下载 `code_llama` 需要在官网进行邮件申请，国内邮箱不好通过，建议使用 Gmail/Outlook

> 申请地址：https://ai.meta.com/resources/models-and-libraries/llama-downloads/

等待五分钟，会收到以下邮件，表示申请通过了：

![](https://github.com/danielchan-25/AI-ProJect/blob/main/img/code_llama-1.png)

注意保存红色方框里的地址，下载模型时要用。

当申请邮件通过后，记得24小时内将模型下载到本地，否则需要再次邮件申请。

### 克隆项目

```bash
git clone https://github.com/facebookresearch/codellama.git
```

将项目下载到服务器后，然后执行：`bash download.sh`

1. 出现 `Enter the URL from email:` 时，输入邮件中的链接地址。

2. `Enter the list of models to download without spaces (7b,13b,34b,7b-Python,13b-Python,34b-Python,7b-Instruct,13b-Instruct,34b-Instruct), or press Enter for all:` 我选择的是`7b` `7b-Python` 两个模型，输入后开始下载，接下来就是漫长的等待。

![](https://github.com/danielchan-25/AI-ProJect/blob/main/img/code_llama-2.png)
