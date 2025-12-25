





## build images
```bash
docker image build -t `<nome de l'image>`
```

## deploy a service on a stack
** create a stack with services
```bash
docker stack deploy --compose-file docker-compose.yaml <nom de stack>
```

## list stack
```bash
docker stack ls
```

## list service on stack
```bash
docker stack services <nom de stack>
```

## list containers under services
```bash
docker services ps <nom de service>
```

