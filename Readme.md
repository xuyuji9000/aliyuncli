# aliyuncli

This project contain doc for aliyuncli usage.

## Commonly Used Info

- Image id

  ubuntu 16.04: *ubuntu_16_0402_64_20G_alibase_20170818.vhd*
  ubuntu 14.04: *ubuntu_14_0405_64_20G_alibase_20170824.vhd*

## Commands

- Get Ubuntu image id
  
    `aliyuncli ecs DescribeImages --RegionId ap-southeast-1 --ImageOwnerAlias system --OSType linux --Architecture x86_64 --ImageName ubuntu*  --filter Images.Image[*].ImageName`
