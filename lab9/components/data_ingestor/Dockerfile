FROM python:3.7
ADD component.py ./
ADD requirements.txt ./
RUN pip install -r requirements.txt
ENTRYPOINT ["python", "./component.py"]