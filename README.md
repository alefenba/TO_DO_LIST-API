# Criando seu ambiente virtual
python -m venv .venv
# Ative o ambiente virtual
.venv\Scripts\Activate.ps1
# Instalando dependencias
python -r requirements.txt
# Rodando o servidor local
uvicorn ToDO:app --reload
# Acessando pelo navegador
127.0.0.1:8000/docs
