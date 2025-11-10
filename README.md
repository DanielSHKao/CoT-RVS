
# CoT-Seg 
> [**CoT-Seg: Rethinking Segmentation with Chain-of-Thought Reasoning and Self-Correction**](https://danielshkao.github.io/CoT-Seg/preprint.pdf)     
> Shiu-hong Kao, Chak Ho Huang, Huaiqian Liu, Yu-Wing Tai, Chi-Keung Tang       
> [Project page](https://danielshkao.github.io/cot-seg.html)

<img width="800" alt="image" src="https://github.com/user-attachments/assets/04dcfe23-e97d-40b6-a0ea-cdbbca8f9cb7" />

CoT-Seg is a a training-free framework that rethinks reasoning segmentation by combining chain-of-thought reasoning with self-correction. 
CoT-Seg leverages the inherent reasoning ability of pre-trained MLLMs
(e.g., GPT-4o) to decompose queries into meta-instructions, extract fine-grained
semantics from images, and identify target objects even under implicit or complex
prompts. Crucially, CoT-Seg incorporates a self-correction stage: the model evaluates its own segmentation against the original query and reasoning trace, identifies mismatches, and iteratively refines the mask.

---
Our code will be released soon.

## Demo
<img width="700" alt="image" src="https://github.com/user-attachments/assets/77e00d7e-8c3a-4e69-a412-9b8a73868bc5" />

View more examples in our [project page](https://danielshkao.github.io/cot-seg.html).

## Dataset
We propose REASONSEG-HARD, a new evaluation dataset for stress testing reasoning segmentation. To access the dataset, please download it from the following sources:
- [Google Cloud]()
- [OneDrive]()

## Citation
If you find this repository helpful, please consider citing:
```
@article{kao2025cotseg,
    title={CoT-Seg: Rethinking Segmentation with Chain-of-Thought Reasoning and Self-Correction},
    author={Kao, Shiu-hong and Huang, Chak-Ho and Liu, Huaiqian and Tai, Yu-Wing and Tang, Chi-Keung},
    journal={arXiv preprint arXiv:xxxx.xxxxx},
    year={2025}
}
```
