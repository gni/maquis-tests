# maquis tests repo

## build
```bash
docker compose build
```

## run llama.cpp server
```bash
docker compose up -d llama-server
```

## run agent
```bash
docker compose run --rm maquis
```

## config endpoint or provider
```bash
/config
/provider
```