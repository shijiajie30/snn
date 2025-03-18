数据集下载

import kagglehub

# Download latest version
path = kagglehub.dataset_download("shijiajie30/polymer-data")

print("Path to dataset files:", path)

或
#!/bin/bash
kaggle datasets download shijiajie30/polymer-data
