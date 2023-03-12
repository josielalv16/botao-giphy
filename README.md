# botao-giphy

docker run -p 8000:80 josielalv16/botao-giphy:1.0

docker build -f ./Dockerfile -t josielalv16/botao-giphy:1.0 .
docker login -u josielalv16 -p 12321321321
docker push --all-tags josielalv16/botao-giphy