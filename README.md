Air pollution prediction using LLM: 
LLMs are zero shot forecasters and this repo explores the potential of LLM by converting the numeric data in to string format to make it compatible with model. 

1. Data collection file conatains code to perform the data preprocessing steps. Air Quality Index(AQI) Data has been collected form mandir-marg monitoring station. It includes handling missing values and calculation of AQI as it was not given explicitly in the dataset downloaded.
2. A attempt to perform Zero-shot learning was attempted. However, I'm was not able to complete with satisfactory results(due to rate limit of openai) but I can still improve it. 
3. LSTM is implemented for the dataset succesfully. Here I used conventional method with a shift of 7 wherein LSTM model was trained with sequences of 7 days to predict next AQI. At last visualization is shown to compare the predictions and ground truth.
4. [optional] I tried to implement the 'Time Series Transformer' model from hugging face but it didn't have its tokenizer and being novice i found challenges in completing this task.  
