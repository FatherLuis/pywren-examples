# Set Up
In case you have not installed awecli and pywren.

$ pip install awscli

$ pip install pywren

You'll need an Amazon Web Service Account
https://aws.amazon.com/

Once the account has been created, you'll need to create access keys for an IAM user
https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html

Set up awscli on the Command Line
https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html

Set up Pywren on the Command Line
http://pywren.io/pages/gettingstarted.html


For more information on the Amazon Simple Storage Solution (Amazon S3)
https://aws.amazon.com/s3/?nc=sn&loc=1

Free Tier Information
https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc




# pywren examples

This is a repository of pywren examples, showing how to run various
example code and generate many of the plots used in blog posts.
Most examples have an explanation in a `README.md`, a script to run, and
often a [Jupyter notebook](http://jupyter.org/) for interactively examining
results. 

Note that these examples, in addition to requiring the latest pywren, 
often require additional packages like Jupyter/iPython, Matplotlib, Seaborn, 
and the Ruffus pipeline manager. 

# Hello World

[Hello world](hello_world/hello_world.ipynb) is a simple example to
get you up and running with pywren.


# GB/s from S3

It is possible to achieve up to 80 GB/sec read and 60 GB/sec write performance to S3 in this
benchmark example, based on the [original blog post](http://pywren.io/pywren_s3.html). There are
notebooks that [show how to benchmark](benchmark_s3/s3_benchmark.ipynb) 




