FROM python:3.13.0a1-alpine
ARG T=python
COPY . /${T}
WORKDIR /${T}
RUN pip install -r requirements.txt
CMD ${T} ./${T}/app.py
