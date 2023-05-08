from airflow.models import DagBag
dag_ids = DagBag(include_examples=False).dag_ids
for id in dag_ids:
print(id)

https://stackoverflow.com/questions/67895590/get-list-of-all-the-dags-in-python


https://airflow.apache.org/docs/apache-airflow/stable/stable-rest-api-ref.html#operation/patch_connection


https://stackoverflow.com/questions/68723628/dagbag-does-not-populate-dags-as-expected
