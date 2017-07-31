FROM python:2.7-alpine
RUN pip install django
WORKDIR /
RUN mkdir -p /workspace/app/
WORKDIR /workspace/app/
# COPY ./ ./
CMD ["python","manage.py", "runserver"]
