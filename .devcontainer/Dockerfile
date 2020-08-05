FROM python:3.7

WORKDIR /workspace

ADD README.md setup.py Makefile ./
ADD src src
RUN make install
RUN pip install mypy
