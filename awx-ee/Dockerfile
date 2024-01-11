FROM quay.io/ansible/awx-ee:latest
USER 0
WORKDIR /runner
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
ENV PATH="/runner/.local/bin:$PATH"
USER 1000
