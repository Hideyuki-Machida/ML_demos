# ML_demos


## セマンティック検索

### ■ モデルの日本語推論評価デモ
言語モデルを使用して、JSTSデータセットで日本語文ペア推論評価する

* データセット
  * [JGLUE](https://github.com/yahoojapan/JGLUE)

* モデル
  * [MTEB: Massive Text Embedding Benchmark](https://huggingface.co/blog/mteb)

* デモ
  * [JSTSデータセットで日本語文ペア推論評価](JSTSデータセットで日本語文ペア推論評価.ipynb)

### ■ セマンティック検索デモ
日本語文ペア推論評価でスコアの高かった`multilingual_e5_large`を使用してセマンティック検索を行う

* デモ
  * [セマンティック検索_multilingual_e5_large](セマンティック検索_multilingual_e5_large.ipynb)

### ■ 関連
* VectorDB
  * [Pinecone](https://www.pinecone.io/)
  * [Qdrant](https://qdrant.tech/)
  * [ChromaDB](https://www.trychroma.com/)

* LLMでアプリケーションを作成するためのライブラリ
  * [LangChain](https://www.langchain.com/)
  * [LlamaIndex (GPT Index) ](https://github.com/jerryjliu/llama_index)



## 類似画像検索

### ■ 類似画像検索デモ
* データセット
  * [Tiny ImageNet](https://paperswithcode.com/dataset/tiny-imagenet)

* モデル
  * [ResNet-50](https://pytorch.org/vision/main/models/generated/torchvision.models.resnet50.html)

* デモ
  * [類似画像検索_ResNet_50](類似画像検索_ResNet_50.ipynb)

### ■ 関連
* VectorDB
  * [Pinecone](https://www.pinecone.io/)
  * [Qdrant](https://qdrant.tech/)
  * [ChromaDB](https://www.trychroma.com/)
