# Neural Net Classifier
A case study of different approaches to a simple classifier. Trying different pre-trained layers while tweaking some parametres to reach a high accuracy.

## Classes
- Cucumber
- Zucchini
- Orange

## Data
- The data for this project was scraped from the web using the Imageye extension in Chrome. Every image was filtered by medium and large sizes to avoid downloading thumbnails.

- Directory Structure:
    ```
    |-- test
        |-- cucumber
        |-- zucchini
        |-- orange
    |-- train
        |-- cucumber
        |-- zucchini
        |-- orange
    |-- val
        |-- cucumber
        |-- zucchini
        |-- orange
    ```
# Usage
1. pip3 install -U jupyter matplotlib numpy pandas scipy scikit-learn tensorflow || python3 -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn tensorflow
2. Verify install with  python3 -c "import jupyter, matplotlib, numpy, pandas, scipy, sklearn, tensorflow". No errors should display.
3. run jupyter notebook. Open link if not automatic
