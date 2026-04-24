commands in windows terminal -

!ngrok config add-authtoken
from pyngrok import ngrok
!streamlit run app.py &>/dev/null &
public_url = ngrok.connect(8501)
public_url
