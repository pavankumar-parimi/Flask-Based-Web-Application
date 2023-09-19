FROM python:3
RUN apt update && apt install git -y
RUN git clone https://github.com/pavankumar-parimi/Flask-Based-Web-Application.git
WORKDIR Flask-Based-Web-Application
RUN pip install --no-cache-dir -r requirements.txt
CMD [ "python3", "flaskMongoApp.py" ]