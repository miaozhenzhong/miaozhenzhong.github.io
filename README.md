<!DOCTYPE html><html>  <head>     <title>个人简历</title>     <meta charset=UTF-8 />     <style type=text/css>   /*声明其内容为标准的css*/       *{          margin: 0;          padding: 0;          border: none;          font-size: 12px;        }  /*”*“为通配符选择器，将所有的元素设置为外边距margin和内边距padding为0，无边框，字体大小为12像素*/            #resume{          width: 800px;          margin: 0 auto;   /*外边距上下为0，左右自适应，为了使DIV在浏览器中水平居中*/          border: solid 1px #DCDDDF;        }       #resume .one{          background: url(beijing.jpg);          width: 800px;          height: 90px;          font-size: 30px;          color: red;          font-weight: bold; /*定义粗体字符*/          text-align: center;          margin-bottom: 0; /*下外边框设置为0*/          line-height: 90px;        }		       #resume ul{          width: 780px;          margin-left: 13px;          margin-top: 20px;        }       #resume ul li{          font-size: 20px;          background: url(li.png) no-repeat;/*设置图片不重复*/          list-style: none;          text-indent: 2em; /*规定文本块中首行文字的缩进，em为相对单位*/          line-height: 30px;   /*行间距离为30像素*/          margin-bottom: 20px;          border-bottom: 1px solid #DCDDDF;        }       #resume ul li.none1{          border-bottom: none;  /*将id为resume中的ul 且class为none1的li去掉下边框*/        }       #resume ul li p{          font-size: 15px;        }  /*将id为resume中的ul li 下的p标签的字体设置为15像素*/     </style></head><body>    <div id="resume">     <div class="one">个人简历</div>     <ul>       <li>个人信息         <p>           姓名：李明;           性别：男;           籍贯：山东聊城;           年龄: 23;         </p>         <p>           手机：134xxxxxxxx;           学校：XXXX大学;           专业：XXXXXX;           学历：XX;         </p>       </li>       <li>教育背景         <p>           2012.9-2016.6: XXXX大学XXX专业         </p>         <p>           在这里学习到了……         </p>       </li>       <li>社会经历         <p>           2015.7-2016.5: xxx公司xxx岗位实习         </p>         <p>           工作内容……         </p>       </li>       <li>专业技能         <p>           考取了XXX证书……获奖情况……         </p>       </li>       <li>相关资格证书         <p>计算机证书</p>         <p>教师资格证书</p>         <p>营养师证书</p>         <p>英语竞赛证书</p>       </li>       <li class="none1">自我评价         <p>           中肯、客观的自我评定……         </p>       </li>     </ul>    </div></body></html>
