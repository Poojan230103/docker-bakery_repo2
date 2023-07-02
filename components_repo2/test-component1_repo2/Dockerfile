# pandas_img:1.0

FROM pip_img:1.0

WORKDIR /app

COPY ./components_repo2/test-component1_repo2/requirements.txt .

RUN pip install -r requirements.txt

ENTRYPOINT ["/bin/sh", "-c", "while true; do sleep 5; done"]
