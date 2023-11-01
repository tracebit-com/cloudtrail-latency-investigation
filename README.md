# Cloudtrail latency investigation

Jupyter notebook for investigating cloudtrail latency using Athena and matplotlib.

## Setup

```
pip install -r requirements.txt
jupyter lab
```

## Use

You'll already need a suitably partitioned athena table for cloudtrail data.

Configure the following options in the notebook:

```
AWS_PROFILE = ""
CLOUDTRAIL_ATHENA_TABLE_NAME = ""
CLOUDTRAIL_ATHENA_WORKGROUP = ""
CLOUDTRAIL_ATHENA_DATABASE = ""
CLOUDTRAIL_ATHENA_CATALOG = ""
```
