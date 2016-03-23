# python-ecs-example
Python example using Boto3 to deploy WordPress and a MySQL instance to Amazon EC2 Container Service (ECS)

# Usage
1. Edit `deployment.py` and enter your AWS access key and secret.

2. Run the following code in the main directory, to create a virtual environment and install all requirements with pip.

```bash
virtualenv --no-site-packages --distribute .env && source .env/bin/activate && pip install -r requirements.txt
```
# License
MIT (c) 2016 - Kevin Goedecke
