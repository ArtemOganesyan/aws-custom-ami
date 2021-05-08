# Creating a custom AMI to use with AWS EC2

**Prerequisites:**
* Prepared VirtualBox VM image in VHD format.
* Installed and configured AWS CLI

**Variables**
| +++RoleName+++ | Name of a role to be used on AWS |
| | |

* +++BucketName+++
    * Name of your S3 bucket where necessary files will be placed
* +++PathToVhdFile+++
    * Name (if file is in root directory of your bucket) or a path to VHD file (ex. folder/filename.vhd)
