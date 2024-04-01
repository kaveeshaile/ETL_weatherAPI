# ETL_weatherAPI

Steps

1.create and config EC2 instance.
2.connect ec2 using following cmd with airflow.

sudo apt update
sudo apt install python3-pip
sudo apt install python3.10-venv
python3 -m venv airflow_venv
sudo pip install pandas
sudo pip install s3fs
sudo pip install apache-airflow
airflow standalone

2nd part ---

sudo apt  install awscli
aws configure
aws sts get-session-token

3.check the airflow.
4.connect .SSH host and other things.
5.dap.py update.
6.create newconnection inside airflow.
7.added operator to transform data.
8.convert data to DF >>csv
9.s3 buket createandconfig with access keys and give credentials.
10.run airflow dag....
