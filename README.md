[![Grid.ai BYOC Create](https://github.com/gridai-actions/gridai-byoc/actions/workflows/unittest.yml/badge.svg)](https://github.com/gridai-actions/gridai-byoc/actions/workflows/unittest.yml)

WARNING WARNING WARNING

Fork and make the forked repo private before running the unittest.

WARNING WARNING WARNING

Grid.ai Create Cluster in your VPC using GitHub Composite Action

- `grid edit cluster` and `grid clusters aws --edit-before-creation` are used to view and optionally modify the cluster configuration.  
`EDITOR` environment variable is used to call the program for this purpose.
`EDITOR` is typically not set and defaults to `vim`. 
`sed` will be used in below examples for automation and reproduciton.

- AMI 
'builder_ami_override': 'ami-076aff9d2e3ed3f8d',
'cpu_ami_override': 'ami-0ee7f482baec5230f',
'gpu_ami_override': 'ami-06ca59652d29b5d92',