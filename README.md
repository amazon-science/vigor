## ViGoR: Improving Visual Grounding of Large Vision Language Models with Fine-Grained Reward Modeling (ECCV 2024)

This repository contains the evaluation dataset of image descriptions as described in the [paper](https://arxiv.org/pdf/2402.06118). This dataset contains paragraph-length descriptions of MSCOCO images, along with human annotated judgment of each description's correctness relative to the corresponding image and its creativity. The dataset is provided in the standard JSON format. 

## Attributions

The underlying images were selected from [MS-COCO](https://cocodataset.org). 
The model used to generate the descriptions is LLaVA. The underlying LLM is based on [LLaMA v1](https://github.com/meta-llama/llama/tree/llama_v1) by Meta (see the applicable [license agreement](LLaMA_LICENSE_AGREEMENT.docx)). 

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This dataset is licensed under the CC-BY-NC-4.0 License. See the [LICENSE](LICENSE.txt) file.

## Citation: Bibtex
```
@inproceedings{yan-eccv2024-vigor,
    title = "ViGoR: Improving Visual Grounding of Large Vision Language Models with Fine-Grained Reward Modeling",
    author = "Yan, Siming  and
      Bai, Min and 
      Chen, Weifeng and 
      Zhou, Xiong and 
      Huang, Qixing and 
      Li, Erran",
    booktitle = "Proceedings of European Conference on Computer Vision 2024",
    year = "2024",
    url = "https://arxiv.org/abs/2402.06118",
}
```
