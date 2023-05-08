from airflow.models import DagBag
dag_ids = DagBag(include_examples=False).dag_ids
for id in dag_ids:
print(id)

https://stackoverflow.com/questions/67895590/get-list-of-all-the-dags-in-python


https://airflow.apache.org/docs/apache-airflow/stable/stable-rest-api-ref.html#operation/patch_connection


https://stackoverflow.com/questions/68723628/dagbag-does-not-populate-dags-as-expected

http://ec2-13-230-185-152.ap-northeast-1.compute.amazonaws.com:8080

https://zhuanlan.zhihu.com/p/120732877

https://www.cnblogs.com/lightsong/p/14991297.html

https://zhuanlan.zhihu.com/p/433681028
