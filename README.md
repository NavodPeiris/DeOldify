download model for colorization by this url: https://data.deepai.org/deoldify/ColorizeArtistic_gen.pth

then place the model **ColorizeArtistic_gen.pth** inside DeOldify/src/models folder

**pip install -r requirements.txt**
      - this will install the required packages

**cd src**
**uvicorn test:app --host 0.0.0.0 --reload**
    - this will start server