## Notice

The VM in this repository has been removed. Please download it here:
https://drive.google.com/open?id=0BwB5sVwXtBneY21Pb2NGVW9yT0E, which is a 
tarball of all the VM images.

======================================

##### VM

The VM is used for FSE'16 Artifacts Evaluation for paper BidText. It is created
using Oracal VM VirtualBox (https://www.virtualbox.org/) 5.0.14.

##### How to download the VM

Due to the size of the VM images (>1GB), we leverage Git LFS (https://git-lfs.github.com/)
to store the files. The users should install Git LFS before cloning the repository.
With Git LFS installed, the users can download the VM images via "git lfs clone"
or "git lfs pull".

##### Login

username: ubuntu

password: bidtext

##### Comment

The default setting for max JVM heap memory is 4GB (in bidtext.prop),
which is not enough for BidText to run on arbitary Android apps, including
the 100 test apps. The users are expected to change the settings to 
set a larger memory size for the VM when creating it as well as for BidText
when running it.

