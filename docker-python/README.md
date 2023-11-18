### Para criar imagem docker (a partir do diretorio atual)

```bash
docker build -t <nome_da_imagem> .
```

### Para executar imagem docker

```bash
docker run -p 5000:5000 <nome_da_imagem>
```