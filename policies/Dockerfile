FROM docker.io/openpolicyagent/opa:latest

WORKDIR /app/opa/policies

COPY . .

CMD ["run", "--server", "--bundle", "."]
