<h3 style="text-align:center">Serverless Example Todo using Serverless Framework and Localstack</h3>
<hr>

1. Install localstack

```cmd
pip install localstack
```

2. Install serverless

```cmd
npm install -g serverless
```

3. Install docker

[Docker Install Tutorial](https://docs.docker.com/desktop/windows/install/)

4. Run

```cmd
    
    # Start localstack run on docker container
    localstack start
    # server deploy on localstack
    serverless deploy --stage local
    
```




