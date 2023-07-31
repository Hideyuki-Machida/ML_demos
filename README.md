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
  * [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hideyuki-Machida/ML_demos/blob/main/JSTS%E3%83%87%E3%83%BC%E3%82%BF%E3%82%BB%E3%83%83%E3%83%88%E3%81%A7%E6%97%A5%E6%9C%AC%E8%AA%9E%E6%96%87%E3%83%9A%E3%82%A2%E6%8E%A8%E8%AB%96%E8%A9%95%E4%BE%A1.ipynb)


### ■ セマンティック検索デモ
日本語文ペア推論評価でスコアの高かった`multilingual_e5_large`を使用してセマンティック検索を行う

* デモ 
  * [セマンティック検索_multilingual_e5_large](セマンティック検索_multilingual_e5_large.ipynb)
  * [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hideyuki-Machida/ML_demos/blob/main/%E3%82%BB%E3%83%9E%E3%83%B3%E3%83%86%E3%82%A3%E3%83%83%E3%82%AF%E6%A4%9C%E7%B4%A2_multilingual_e5_large.ipynb)


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
  * [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hideyuki-Machida/ML_demos/blob/main/%E9%A1%9E%E4%BC%BC%E7%94%BB%E5%83%8F%E6%A4%9C%E7%B4%A2_ResNet_50.ipynb)


### ■ 関連
* VectorDB
  * [Pinecone](https://www.pinecone.io/)
  * [Qdrant](https://qdrant.tech/)
  * [ChromaDB](https://www.trychroma.com/)

## レコメンデーション

### ■ 映画推薦システムデモ
* 元のPineconeドキュメントとGoogle Colab Notebook
  * [Pinecone - Movie Recommender](https://docs.pinecone.io/docs/movie-recommender)
  * [Colab](https://colab.research.google.com/github/pinecone-io/examples/blob/master/recommendation/movie-recommender/00_movie_recommender.ipynb)

* デモ
  * [Movie_Recommender_Qdrant.](Movie_Recommender_Qdrant.ipynb)
  * [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hideyuki-Machida/ML_demos/blob/main/Movie_Recommender_Qdrant.ipynb)

  