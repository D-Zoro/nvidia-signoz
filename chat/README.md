to run signoz :

    cd signoz
 
    docker compose up -d

to run app:

    opentelemetry-instrument \
        --traces_exporter otlp \
        --metrics_exporter otlp \
        --service_name nvidia-chatbot \
    streamlit run main.py

other steps(skill issue):

    copy .env
    have uv
    uv sync
  
