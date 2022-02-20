## [Odoo/Tryton - Neural Machine Translation][Notebook] &nbsp;&nbsp; [![License: MIT][License-Badge]](LICENSE)
This **Colab** created to make it easier for Odoo/Tryton developers and to show the good results that can be obtained using new technologies.
You can translate from English to +100 other languages with only uploading the English base PO file.

I use two pre-trained models:
- [![Open in Colab][Colab Badge]][Notebook] [Opus-MT][Opus-MT]: 186 Languages & 300MB size (Quick Translation & lightweight)
- [![Open in Colab][Colab Badge]][Notebook2] [m2m_100_1.2B][m2m_100_1.2B] (Facebook Research): 100 Languages & 5GB size (Recommended by [EasyNMT][EasyNMT])

| Model        | Reference                                                                            | #Languages |  Size  | Speed GPU (Sentences/Sec on V100) | Speed CPU (Sentences/Sec) | Comment                                                |
|--------------|--------------------------------------------------------------------------------------|:----------:|:------:|:---------------------------------:|:-------------------------:|--------------------------------------------------------|
| opus-mt      | [Helsinki-NLP](https://github.com/Helsinki-NLP/Opus-MT)                              |    186     | 300 MB |                50                 |             6             | Inidivudal models  (~300 MB) per translation direction |
| m2m_100_1.2B | [Facebook Research](https://github.com/pytorch/fairseq/tree/master/examples/m2m_100) |    100     | 5.0 GB |                13                 |             -             |                                                        |

I also invite you to make some small modifications in the Notebook to be able to translate any type of text/file :)

### Support
1. **Star this repository** 
2. **Contribute to this repository**
3. **Help others 😃**


### Thanks to the [UKPLab/EasyNMT][EasyNMT] Team for the great and laborious work done

[Colab Badge]:          https://colab.research.google.com/assets/colab-badge.svg
[License-Badge]:        https://img.shields.io/badge/License-MIT-blue.svg
[Notebook]:     https://colab.research.google.com/github/JonatanGk/Odoo-Tryton-NMT/blob/main/Odoo_Tryton_Neural_Machine_Translation.ipynb#
[Notebook2]:     https://colab.research.google.com/github/JonatanGk/Odoo-Tryton-NMT/blob/main/Odoo_Tryton_Neural_Machine_Translation_m2m_100.ipynb#
[Opus-MT]:      https://github.com/Helsinki-NLP/Opus-MT
[m2m_100_1.2B]:      https://github.com/pytorch/fairseq/tree/master/examples/m2m_100
[EasyNMT]:          https://github.com/UKPLab/EasyNMT
