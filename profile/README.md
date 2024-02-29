
![](https://github.com/DipperAI/DipperAI/blob/main/docs/images/banner.png)

DipperAI revolutionizes AI model deployment with a serverless Model-as-a-Service framework, enabling instant access and execution of machine learning models directly from hubs like Hugging Face and ModelScope. By eliminating the complexities of model setup, deployment, and maintenance, DipperAI offers a straightforward Python API for seamless integration and use. It caters to developers and data scientists seeking efficiency, flexibility, and scalability in AI projects, providing cost-effective solutions with its serverless architecture. Open-source and community-driven, DipperAI simplifies machine learning, making it accessible and adaptable for a wide range of applications. Join us in shaping the future of AI, where deploying and using AI models is as easy as a few lines of code:

```python
from dipperai.maas import modelscope
model_url = "https://modelscope.cn/models/iic/cv_resnet18_card_correction/summary"
ocr = Modelscope(model_url).invoke("image url")
```
