In this project, we extract data from Reddit through it's API and PRAW module of Python. And then the data is uploaded onto AWS S3 buckets. This whole process is automated through Apache Airflow. And Airflow itself is run on Docker. After the data is uploaded onto the S3 bucket, I crawled through the data using AWS Glue and then did some analysis on it with Athena. 
For the purpose of Demonstration I chose 'r/anime' subreddit, but we can choose which sub we want to extract the data from, how many fields we need, and the time of the posts.
So, this project demonstrates practical application of Airflow, Docker, APIs, AWS (S3, Glue, Athena).
Docker:
![Screenshot (375)](https://github.com/ManishSirikonda/Reddit_data_s3_through_airflow/assets/142118235/fb4dc4fc-fe5e-4c0d-9353-967e9557a7fe)
Airflow: 
![Screenshot 2024-02-25 221631](https://github.com/ManishSirikonda/Reddit_data_s3_through_airflow/assets/142118235/75c0d143-178f-462c-8603-8f99da91fc6e)
The extracted CSV file
![Screenshot (376)](https://github.com/ManishSirikonda/Reddit_data_s3_through_airflow/assets/142118235/7b681e0f-363b-4df4-b13e-62b819fdaa8b)
S3 Bucket
![Screenshot 2024-02-25 221837](https://github.com/ManishSirikonda/Reddit_data_s3_through_airflow/assets/142118235/10bd5ae9-38ab-491f-9328-b5305f898de9)
Athena
![Screenshot 2024-02-25 222033png](https://github.com/ManishSirikonda/Reddit_data_s3_through_airflow/assets/142118235/366c980b-d7d6-4437-9d30-ceff52e94c12)
![Screenshot 2024-02-25 2221311](https://github.com/ManishSirikonda/Reddit_data_s3_through_airflow/assets/142118235/6234eb5a-cda1-4fd5-a751-7f9905690a03)
