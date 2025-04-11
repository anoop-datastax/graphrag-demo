# graphrag-demo

1. Ensure Python ≥ 3.10.14 is installed
2. Create a virtual environment if using Jupyter:
`mkdir graphrag-demo
cd graphrag-demo
python3 -m venv .venv
source .venv/bin/activate`

3. Creatae reuirements.txt file:
   `Langchain-graph-retriever
Python-dotenv
Pyvis
Networkx
Langchain_astradb
Langchain_openai
Matplotlib
Boto3
Pypdf
Gliner
keybert
jupyter
ipykernel
`

4. pip install -r requirements.txt

5. Make the Environment Available to Jupyter

`python -m ipykernel install --user --name=graphrag-demo --display-name "Python (GraphRAG)"`

6. Create .env File
Create a .env file inside your project folder and fill it with your credentials:
OPENAI_API_KEY=your_openai_key
ASTRA_DB_API_ENDPOINT=your_endpoint
ASTRA_DB_DATABASE_ID=your_db_id
ASTRA_DB_APPLICATION_TOKEN=your_token
ASTRA_DB_KEYSPACE=your_keyspace
ASTRA_DB_COLLECTION=your_collection
ASTRA_DB_EMBEDDING_DIMENSIONS=1536
AWS_ACCESS_KEY_ID='AKxxx'
AWS_SECRET_ACCESS_KEY='jn=='

7. Launch Jupyter Notebook

`jupyter notebook` and run the Hello world script to check your setup. 

8. Execute the main demo script. 
