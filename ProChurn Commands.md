## Run Training CLI Command Example
<!-- REFER TO README FOR ARGUMENTS DEFINITIONS --> 
python src/train_pipeline.py --company Telco_A --data data/"Data-Example-1.csv" --test_size 0.3
python src/train_pipeline.py --company Telco_B --data data/"Data-Example-2.csv" --test_size 0.3

## Run Predict CLI command Example
<!-- REFER TO README FOR ARGUMENTS DEFINITIONS --> 
python src/predict_pipeline.py --company Telco_A --data data/"Data-Example-1.csv" --demo
python src/predict_pipeline.py --company Telco_B --data data/"Data-Example-2.csv" --demo

## Ollama Hosting Commands
<!-- Ollama must be Locally downloaded -->
ollama pull llama3.2
ollama serve
taskkill /IM ollama.exe /F