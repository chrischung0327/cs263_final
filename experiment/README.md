### calculate_retrieval_score.py
Calculates the retrieval score of each head in every layer in a given model. (Llama 3.2 1B Instruct) Results are stored in ```/results/head_score/<model_name>.json```

#### Usage
```
python calculate_retrieval_score.py
```

### plot_head_score
Plots the distribution of head scores in Llama 3.2 1B Instruct. Chart stored in ```/results/plots/```
#### Usage
```
python plot_head_score
```

### print_top_head.py
Print heads with the top 10 highest retrieval scores in Llama 3.2 1B Instruct. 

#### Usage
```
python print_top_head.py
```