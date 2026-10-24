# Schnauzer (슈나우저) language packs

Translation models that the Schnauzer screen translator for Windows downloads when you add a language in
Settings › Languages. Each zip holds one translation direction for [CTranslate2](https://github.com/OpenNMT/CTranslate2).

## Models and license

All models are [OPUS-MT](https://github.com/Helsinki-NLP/OPUS-MT-train) models from the
[Tatoeba Translation Challenge](https://github.com/Helsinki-NLP/Tatoeba-Challenge) by Helsinki-NLP
(University of Helsinki, Jörg Tiedemann et al.), released under the
[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.

**Changes made:** each original Marian release was converted to the CTranslate2 format and quantized to int8, and a
`schnauzer.json` file (direction and target-language label) was added. The original authors do not endorse Schnauzer.

| Direction | File | Size | SHA-256 | Original release |
| --- | --- | --- | --- | --- |
| en-ja | en-ja.zip | 65 MB | `aa40de202c16a981d2dbfb45120db088c87e9355b85fcc232223e31a17631d1f` | [eng-jpn](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-jpn/opus+bt-2021-04-10.zip) |
| ja-en | ja-en.zip | 69 MB | `a9c114e3dcf6f560cb05318471c4b3e43a6a3e1a2b1630c40ffeeb4430862a32` | [jpn-eng](https://object.pouta.csc.fi/Tatoeba-MT-models/jpn-eng/opus-2021-02-18.zip) |
| en-zh | en-zh.zip | 224 MB | `48555115a496baed8dbf9f2e78a0a71ca427034171cd4775bf19728336fcf114` | [eng-zho](https://object.pouta.csc.fi/Tatoeba-MT-models/eng-zho/opusTCv20210807+bt_transformer-big_2022-05-14.zip) |
| zh-en | zh-en.zip | 74 MB | `1042d8339f7963221a0afe1de7f8e531132511531beb1eb2411adf26335a8911` | [zho-eng](https://object.pouta.csc.fi/Tatoeba-MT-models/zho-eng/opus+bt-2021-04-30.zip) |
| ja-ko | ja-ko.zip | 202 MB | `88dc67b05e5e9edd49c77da94bc21cffffbfc231daed9570f2e5c09a2c4d93f2` | [jpn-kor](https://object.pouta.csc.fi/Tatoeba-MT-models/jpn-kor/opusTCv20210807-sepvoc_transformer-big_2022-09-15.zip) |
| zh-ko | zh-ko.zip | 202 MB | `56b9c9d8978522f55202e034eda16871bbedaae90a6bfb559e9c82e04b861d8f` | [zho-kor](https://object.pouta.csc.fi/Tatoeba-MT-models/zho-kor/opusTCv20210807-sepvoc_transformer-big_2022-09-15.zip) |
| ja-zh | ja-zh.zip | 212 MB | `5c7dc6f91eb7c3a10f7c11d8b4fef2f5e03f2d737d75a48b71d71c2ee4d86844` | [jpn-zho](https://object.pouta.csc.fi/Tatoeba-MT-models/jpn-zho/opusTCv20210807_transformer-big_2022-09-15.zip) |
| zh-ja | zh-ja.zip | 201 MB | `0534d620bc2bb440541bd1951e295fee91200de78141c23679fffcd02d4b4b9e` | [zho-jpn](https://object.pouta.csc.fi/Tatoeba-MT-models/zho-jpn/opusTCv20210807-sepvoc_transformer-big_2022-07-28.zip) |

If you use these models in research, please cite: Jörg Tiedemann and Santhosh Thottingal, "OPUS-MT — Building open
translation services for the World", EAMT 2020; Jörg Tiedemann, "The Tatoeba Translation Challenge", WMT 2020.
