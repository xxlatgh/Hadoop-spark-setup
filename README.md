# Hadoop-spark-setup

Thank Austin for the nice note. 

I wrote a Jupyter notebook that covers these steps and enables however many nodes you want without going through 
the hacking of terminal group input.

You can spin this up entirely within your Jupyter notebook, but you do need to install boto3 and awscli, and setting up the aws_access_key_id and aws_secret_access_key through *your terminal* (‘pip install awscli’ then ‘aws configure’). 

(A similar notebook setting up Spark is also there, but I did not finish the port-forwarding part so that you can run your Jupyter notebook harnessing the cluster).

[Reference](https://medium.com/@dapingdu/thank-austin-for-the-nice-note-1c8c48f157e5)
