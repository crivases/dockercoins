FROM python:3-alpine@sha256:5beb4823c653c428379bc8b811ef233b7171806e8b10bb6879e7af1ed5bb4093
RUN pip install redis && pip install requests
COPY worker.py /
ENTRYPOINT ["python"]
CMD ["worker.py"]
