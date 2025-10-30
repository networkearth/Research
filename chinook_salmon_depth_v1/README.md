## Data and Models

- `features_{case}.parquet` - features used for inference and model evaulation.
- `contrasts_{case}.parquet` - features used for training
- `model_{name}_features_inference.parquet` - inference over `features` using model `{name}`
- `Results.ipynb` - how plots/tables were generated from the `networkearth` database (included here for context)
- `projection_inferences/` - inference over the whole of the Northern Pacific, organized into partitions of snappy compressed parquet files
- `models/` - the models themselves (keras files and metadata)