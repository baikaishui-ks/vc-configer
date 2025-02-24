步骤：
  1、生成应用包 xxx.exe，得到 A。上传A到版本资源服务器，得到url路径AU
  2、创建版本html说明文档：imic-relnots-vx.x.x.html，得到B。上传B到版本资源服务器，得到URL路径BU
  3、使用winspakle生成A的签名，得到签名C。winspakle路径：D:\project\thirdparty\winsparkle\bin
  3、修改imic-appcast.xml文档内的说明，将版本号进行修改，将AU、BU、C填入相应字段