# quote-search

TensorflowJS powered quote search.

## Deployment

All datasets and configuration are stored in the repo.

To use locally, simply open public/index.html in any web browser supported by TensorflowJS.

Alternatively, the files can be hosted as a static site. On their first visit, it may take clients a while to load the 37MB dataset with embeddings.

## Contributing

Datasets in public/data are generated by running the build command.

```
npm i
npm run build
```

These should be committed to the repo for convenience.
