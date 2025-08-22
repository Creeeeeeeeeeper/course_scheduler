## Course Scheduler

有issue可以直接写，大概一天之内就会回复

代码懒得在这里传了，有任何疑问可联系邮箱2339448077@qq.com

# 使用

首先打开程序，界面如下：
<img width="1502" height="1336" alt="image" src="https://github.com/user-attachments/assets/3a27974c-35b4-46e6-9ce1-aab78ce3f725" />


## 创建项目

点击创建项目即可，然后点击其中一个项目可以选中这个项目。

点击后会显示选中了哪个项目。

<img width="1500" height="1334" alt="image" src="https://github.com/user-attachments/assets/49332dca-1bd4-44ef-a3ce-0ca0a3903005" />


## 教师数据

教师数据需要为一个Excel表，Excel表的格式必须按照下面图中的格式：

（图中名字均为随机出的名字）

<img width="1259" height="962" alt="image" src="https://github.com/user-attachments/assets/8f99c218-bde7-4733-aaf3-8d8c37576899" />


`A1`单元格必须是`年级班级`，下面这一列必须是`x.x`的格式，如果是`十班`，注意要把单元格格式改成文本，必须显示2.10。

后面的表头就是上的科目，下面是教每个科目每个班是哪个老师，应该不难看懂。

如果这个班级不上这一门课（比如图中的一二年级都不上`信息技术`就不用写）

上传之后就会显示在页面上：

<img width="2560" height="1536" alt="image" src="https://github.com/user-attachments/assets/b03a0533-d29b-4964-98c4-8f9d15f9f56b" />


## 课时配置

点击添加科目，这里填的必须要跟Excel表中的表头完全一致。

比如只需要小学的，那么七八九年级的就不用管。

<img width="2560" height="1540" alt="image" src="https://github.com/user-attachments/assets/a7b6d02b-8276-406e-973e-f088a3efcfe9" />


下面这部分是每个年级所有科目加起来的课时数，也就是每个年级的周课时数。

比如这个学期每周五天，每天六节课，那么应该都是`30节课`。

<img width="1854" height="461" alt="image" src="https://github.com/user-attachments/assets/6f3e1f98-23e1-4b04-9472-740c156474c8" />


设置好记得点保存配置！



## 约束配置

这个第一个可以不用管，说实话不太好理解

<img width="1715" height="384" alt="image" src="https://github.com/user-attachments/assets/92153c60-5395-4955-b8a7-2934ef2230c5" />


每日必修，这个必须要周课时数大于等于5的才能并且**必须**在这里写。

<img width="1716" height="379" alt="image" src="https://github.com/user-attachments/assets/5d2664b5-5682-4f05-9fb9-488acee69732" />


每日课时限制，第一个5表示周课时数大于5的科目，第二个表示周课时数大于5的科目每天最多上两节，比如语文有7节课，那么一定有两天是上两节课的，而且最多上两节，不会出现四天上一节，一天上三节的情况。

<img width="1713" height="315" alt="image" src="https://github.com/user-attachments/assets/82e1d8e4-d3ab-44b0-b1cc-2fee367825dd" />

时间段禁排，这个很好理解

<img width="1715" height="719" alt="image" src="https://github.com/user-attachments/assets/f34dddb3-4686-4071-abcc-bf1ad65c1a28" />


偏好设置，这里只写了第一节的偏好，其实比如第一节课偏好主科，那么把副科直接在上面的禁排中禁掉就行

<img width="1714" height="387" alt="image" src="https://github.com/user-attachments/assets/af0b874a-2273-4428-a820-aacdd1708888" />


教师禁排，这个也好理解

<img width="1724" height="716" alt="image" src="https://github.com/user-attachments/assets/03f13544-e535-4015-93c8-f9de98d05b4b" />


最后要先点生成，再点保存

<img width="2560" height="1540" alt="image" src="https://github.com/user-attachments/assets/3093b5bd-e26b-4315-891c-76d8c0329a02" />


## 生成课表

最后点生成课表，目前只支持一周上五天，每天最多8节课的排课

<img width="2560" height="1540" alt="image" src="https://github.com/user-attachments/assets/a954c346-b089-44af-8a2c-0a4a3792a099" />


如果前面设置的没啥问题，那么就可以点开始生成，然后就会有这样的输出：

<img width="1500" height="1334" alt="image" src="https://github.com/user-attachments/assets/1e5d8786-1604-4aaf-9463-4ba53d2926b4" />


如果课时设置错误或者约束过于严格，那么会有以下输出：

<img width="1500" height="1333" alt="image" src="https://github.com/user-attachments/assets/73e87744-f471-4978-b4b5-2df8531760bb" />


## 查看与调整

生成好的课表可以在这里面查看。

<img width="1500" height="1332" alt="image" src="https://github.com/user-attachments/assets/d027e16e-0eea-4f11-974d-926cd3c64e68" />


点进来之后可以查看生成的课表

<img width="2560" height="1540" alt="image" src="https://github.com/user-attachments/assets/a84630c5-11ed-4d83-871d-bf7d973ac63c" />


如果调课的话，右键可以调，会自动识别当前空闲的教师

调课有两种方法，一个是跟本班的其他老师调课，再一个就是同科目老师代课

<img width="2560" height="1540" alt="image" src="https://github.com/user-attachments/assets/e6f26150-fdd7-4b2d-9cd2-6941c8ca310d" />


调完之后可以撤回：

<img width="1784" height="991" alt="image" src="https://github.com/user-attachments/assets/e52b0990-737a-4fb8-84bc-457775742c22" />


最后全部调整完，点击保存即可，这样就会生成一个`xxxx-xx-xx 基于 xxxx 的修改`

点进去之后，就会有对应的修改。在此基础上还可以继续进行修改等操作

<img width="2560" height="1540" alt="image" src="https://github.com/user-attachments/assets/c2ad867b-337e-431e-aff4-ec40a00d5543" />


