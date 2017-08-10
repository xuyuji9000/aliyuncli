# aliyuncli

This project contain doc for aliyuncli usage.

## Commonly Used Info

- Image id

  `ubuntu_16_0402_64_40G_alibase_20170711.vhd`

## Commands

- Get Ubuntu image id
  
  `aliyuncli ecs DescribeImages --PageSize 100 | grep ImageId | grep ubuntu`
