# Description

## This repository is no longer being updated.
### If you want to see moiro_description & mycobot_description, click on the [link](https://github.com/MOIRO-KAIROS/moiro_description).
### If you want to see moi_arm_description, click on the [link](https://github.com/MOIRO-KAIROS/moi_description).

-----------------------------------------------------------------------------------------------------------

Making URDF study
URDF 변환 연습중
참고자료 https://github.com/syuntoku14/fusion2urdf?tab=readme-ov-file
### 주의 사항
mycobot320 모터 회전이 360가 안됨.
-160, 160까지만 됨

moi_arm_description : 스탠드

mycobot_description : agv + mycobot

fusion 360으로 변환시
setup.cfg에서

[develop]
script-dir=$base/lib/moiro_description
[install]
install-scripts=$base/lib/moiro_description
를

[develop]
script_dir=$base/lib/moiro_description
[install]
install_scripts=$base/lib/moiro_description
로 수정
