程序功能介绍：
  本程序根据左右相机矩阵，畸变参数，转换矩阵R，T和左右相机拍摄的图片对，
  进行立体校正，使左右相机拍摄图片的图像平面平行，根据题目要求结果将只展示一组图片，且并不会存储。

程序输入输出介绍：
  本题代码中有三个全局变量：
  1. g_read_photo_list_path_l：左相机拍摄的图片列表
  2. g_read_photo_list_path_r：右相机拍摄的图片列表
  3. g_read_stereoCalibrate_res_path：存放了stereoCalibrate函数输出的左右相机矩阵，畸变参数，转换矩阵R，T

  运行时将数据图片以及left_photo_list.xml,right_photo_list.xml，stereoCalibrate_res.xml放入运行目录即可。
