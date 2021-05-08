# Creating a custom AMI to use with AWS EC2

**Prerequisites:**
* Prepared VirtualBox VM image in VHD format.
* Installed and configured AWS CLI

**Variables**

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

| +++RoleName+++ | Name of a role to be used on AWS |
| | |

* +++BucketName+++
    * Name of your S3 bucket where necessary files will be placed
* +++PathToVhdFile+++
    * Name (if file is in root directory of your bucket) or a path to VHD file (ex. folder/filename.vhd)
