FROM python:3.12
WORKDIR /applicativo
COPY requirements.txt /applicativo
RUN pip install -r requirements.txt
COPY app.py /applicativo
COPY templates /applicativo/templates
EXPOSE 5001
CMD ["python",  "./app.py"]