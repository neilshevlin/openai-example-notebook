# File Uploads Open AI
This is a very simple jupyter notebook for using the openai API. It uses file uploads and asks questions to your uploaded documents from the API. 

## Required
- Jupyter
- openai library
- Python 3^

```bash
    pip install openai
```

## To run the example provided
1. First start by running the notebook 'Text To Jsonl'
2. Run either methods in the notebook 'convertByLine()' or 'convertByFullStop()'
3. This converts the example text file provided in to jsonl format. 
4. Run Upload notebook to upload the json lines document previously converted.
5. Run the Questions file which will ask a sample question of the document you have just uploaded