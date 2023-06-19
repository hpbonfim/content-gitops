FROM python:3-alpine
ARG T=python
COPY . /${T}
WORKDIR /${T}
RUN pip install -r requirements.txt
CMD ${T} ./${T}/app.py
