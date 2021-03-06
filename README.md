# Useful Decorators for Data Science

  
## PySpark

  1. `pyspark_udf` - Converts python3 type hints into PySpark return types and return `PySparkUDF` object.
  
## sklearn
  1. `SKTransform` - Turn any function into an sklearn Transformer, and use it in an sklearn Pipeline.
  1. `SKClassify ` - Turn any function into an sklearn Classifier, and use it in an sklearn Pipeline, can be used also for clustering.
  
## Caching

  1. `json_file` - Save function calls to a json file.
  1. `pickle_file` - Save function calls to a pickle file.
  1. `s3_cache` - Save function calls to amazon s3.
  
## Regression Tests
  1. `regres.record` - Record funcion inputs and outputs.
  1. `regres.replay` - Replay recorded data against a different implementation.
  
## Logging
  1. `log_error` - Logs errors using the `logging` module.
  1. `slack_error` - Sends a slack message when an error occurs.
  1. `telegram_error` - Sends a telegram message when an error occurs.
  
  
## Time
  1. `time_limit` - Limit execution time to `s` seconds.

## SSH connection
  1. `ssh_connect` - Run python code on a remote SSH Server.
