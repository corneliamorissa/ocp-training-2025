FROM python:3.12
WORKDIR /code
RUN pip install flask
COPY word_picker.py /code/word_picker.py
ENV FLASK_APP=/code/word_picker.py
CMD ["python", "-m", "flask", "run", "-h", "0.0.0.0"]