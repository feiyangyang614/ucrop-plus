本库基于https://github.com/Yalantis/uCrop进行微调
由于https://github.com/Yalantis/uCrop的裁剪无法自定义身份证人像和国徽裁剪框，因此在其基础上微改以满足需求
该库的基本使用同https://github.com/Yalantis/uCrop
在 private UCrop advancedConfig(@NonNull UCrop uCrop) 方法中增加以下配置
options.setUCropOverImageDrawable(R.drawable.camera_idcard_front);即可在裁剪时显示身份证人脸识别框
R.drawable.camera_idcard_front即为身份证人脸框