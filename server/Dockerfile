FROM python
RUN pip install --upgrade pip

WORKDIR /server/
ADD . /server/

RUN pip install -r requirements.txt
CMD ["python","app.py"]