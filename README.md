## AWS ElasticBeanstalk Deployment of CarBuddy.

Steps:
- ElasticBeanstalk CLI should be installed.
- Create a virtualenv for ElasticBeanstalk with "virtualenv env" and run "source env/bin/activate".
- Create ElasticBeanstalk application on Docker platform with "eb init -p docker car-buddy". 'car-buddy' here can be any name you want. You should see an ".elasticbeanstalk" folder.
- Deploy the Docker image with with "eb create car-buddy-env".

