# Cloudtrail latency investigation

Jupyter notebook for investigating cloudtrail latency using Athena and matplotlib.

This was used to produce the charts in [How fast is CloudTrail today? Investigating CloudTrail delays using Athena](https://tracebit.com/blog/2023/11/how-fast-is-cloudtrail-today-investigating-cloudtrail-delays-using-athena/)

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
