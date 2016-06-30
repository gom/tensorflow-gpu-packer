# Packing AMI for Tensorflow on EC2 with GPU

* Download cuDNN files from NVIDIA website.
* https://developer.nvidia.com/cudnn
* Put it on ansible/roles/gpu/files/

Please see: https://www.tensorflow.org/versions/master/get_started/os_setup.html#optional-install-cuda-gpus-on-linux

```
$ brew install packer
$ cd $PATH_TO_THIS
$ packer build -var-file=aws.json ec2.yml
```
