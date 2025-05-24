

<img width="763" alt="image" src="https://github.com/user-attachments/assets/71249a9c-cf5f-44a2-b01f-751fe9aaff49" />

### Fire
```
{
  "jobs": [
    {
      "query": "OPTIMIZE mydb.table_1 REWRITE DATA USING BIN_PACK",
      "database": "default",
      "output_location": "s3://XX/athena-result/"
    },
    {
      "query": "OPTIMIZE mydb.table_2 REWRITE DATA USING BIN_PACK",
      "database": "default",
      "output_location": "s3://XX/athena-result/"
    }
  ]
}

```

## Read More
https://medium.com/@shahsoumil519/parallel-iceberg-table-compaction-with-aws-step-functions-and-athena-704e0079037d
