# malicious-url-classification
DaconのAI競技大会で悪性URLを分類するモデルを開発したプロジェクト（Malicious URL Classification with TF-IDF + LightGBM）

# 悪性URL分類プロジェクト（Malicious URL Classification）

このプロジェクトは、韓国のAIプラットフォーム「Dacon」のAI競技大会「悪性URL分類」に参加し、TF-IDFとLightGBMを用いて約700万件のURLを分析・分類した実装記録です。

This project documents my participation in the Dacon AI competition “Malicious URL Classification,” where I used TF-IDF and LightGBM to classify over 7 million URLs.

---

## 📂 構成ファイル / Project Structure

malicious-url-classification/
├── notebooks/
│   └── tfidf_lightgbm_colab.ipynb
├── models/
│   ├── final_model.pkl
│   └── tfidf_vectorizer.pkl
└── README.md

---

## 🚀 使用技術 / Tech Stack

- Python 3.11
- scikit-learn
- LightGBM
- Google Colab
- TfidfVectorizer (char-level n-gram)

---

## 📝 実行方法（Colab環境） / How to Run (Colab)

1. `notebooks/tfidf_lightgbm_colab.ipynb` をGoogle Colabで開く
2. 必要に応じてGoogle Driveをマウントし、データとモデルを配置
3. 上から順にコードセルを実行
4. `submission.csv` が出力されます

---

## 🔗 関連リンク / Related Links

- 📘 [Zenn記事：700万件の悪性URL分類に挑戦](https://zenn.dev/your-article-url)
- 🏆 [Dacon大会ページ](https://dacon.io/competitions/official/236233/overview/description)

---

## 📌 ライセンス / License

This project is licensed under the MIT License.

※ 本プロジェクトでは最終提出ファイルの生成までは至っておりませんが、モデルの構築・評価（ROC-AUC: 0.94095）は完了しています。

