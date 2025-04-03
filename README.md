# Fake News Detection Project

This project builds a fake news detection system using machine learning. It preprocesses news headlines, trains a Naïve Bayes classifier, and predicts whether a headline is real or fake.

## Files
- `Fake_News_Detection.ipynb`: Google Colab notebook with the code and explanations.
- `Fake_News_Detection_Report.pdf`: A short report summarizing the approach, challenges, and performance.
- `fake_news_model.pkl`: Saved Naïve Bayes model.
- `tfidf_vectorizer.pkl`: Saved TF-IDF vectorizer.
- `Dataset`: both true and fake csv files.

## How to Run
1. Open `Fake_News_Detection.ipynb` in Google Colab.
2. Upload the dataset  if not included.
3. Run the cells to preprocess the data, train the model, and test it.

## Results
- Achieved an accuracy of ~93% on the test set.
- Successfully predicts fake news on new headlines.

## License
This project is licensed under the MIT License.
