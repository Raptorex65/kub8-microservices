# Container imajini bu dockerfile ile olusturuyoruz
# Application icin gerekli base program imaji bu ornekte python oldugu icin onu en basta indiriyoruz.
FROM python:alpine
COPY . /app
# COPY directory is true??
WORKDIR /app
RUN pip install -r requirements.txt
# -r : install from requirements file
EXPOSE 80
CMD python ./app.py
