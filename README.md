# test
<!doctype html>
<html>
	<head>
		<meta charset="utf-8">
		<title>简历</title>
		<style>
			@keyframes first{
				0%  {transform:rotateY(0deg) rotateX(0deg) rotateZ(0deg);}
				25% {transform:rotateY(90deg) rotateX(90deg) rotateZ(0deg);}
				50% {transform:rotateY(180deg) rotateX(180deg) rotateZ(0deg);}
				75% {transform:rotateY(270deg) rotateX(270deg) rotateZ(0deg);}
				100%{transform:rotateY(360deg) rotateX(360deg) rotateZ(0deg);}
			}
			.zuo{
				position:fixed;
				top:60px;
				width:100px;
				height:100px;
				border:0px solid #f00;
				perspective:500px;
			}
			.you{
				position:fixed;
				top:60px;
				right:0px;
				width:100px;
				height:100px;
				border:0px solid #f00;
				perspective:500px;
			}
			.zhong{
				margin:24px;
				width:50px;
				height:50px;
				border:0px solid #f00;
				transform-style:preserve-3d;	
				animation:second 2s linear infinite;
			}
			.ge{
				width:50px;
				height:50px;
				border:0px solid #f00;
				position:absolute;
				background-color:#f00;
				text-align:center;
				line-height:50px;
				font-size:40px;
			}
			.front{
				transform:translateZ(24px);
			}
			.back{
				background-image:url(image/简.png);
				transform:rotateX(180deg) translateZ(24px);
			}
			.left{
				transform:rotateY(-90deg) translateZ(24px);
			}
			.right{
				transform:rotateY(90deg) translateZ(24px);
			}
			@keyframes second{
				0%  {transform:rotateY(0deg);}
				25% {transform:rotateY(90deg);}
				50% {transform:rotateY(180deg);}
				75% {transform:rotateY(270deg);}
				100%{transform:rotateY(360deg);}
			}
				.a{
					margin:20px auto;
					width:827px;
					height:1100px;
					border:1px solid #000;
				}
				.b{
					float:left;
					width:200px;
					height:1100px;
					border:0px solid #0f0;
					margin:0px 0px 0px 0px;
					background-color:#244765;
				}	
				.bb{
					width:198px;
					height:248px;
					border:0px solid #00f;
					border-radius:25px;
					line-height:248px;
					text-align:center;
				}
				.bbb{
					width:160px;
					height:448px;
					border:0px solid #00f;
					line-height:30px;
					list-style-type:none;
				}
				.c1{
					
					float:left;
					width:620px;
					height:200px;
					border:0px solid #0f0;	
				}				
				.c11{
					margin:30px 0px 0px 30px;
					float:left;
					width:70px;
					height:70px;
					border:0px solid #0f0;
					text-align:center;
					line-height:70px;
					font-size:49px;	
				}
				.c12{
					float:left;
					width:500px;
					height:50px;
					border:0px solid #f00;
					margin:10px 0px 0px 30px;
					font-size:15px;
					line-height:50px;
				}
				.c2{
					float:left;
					width:594px;
					height:155px;
					border:0px solid #0f0;	
				}							
				.c3{
					float:left;
					width:594px;
					height:200px;
					border:0px solid #0f0;	
				}		
				.c4{
					float:left;
					width:594px;
					height:130px;
					border:0px solid #0f0;	
				}		
				.titles{
					font-size:40px;
					color:#385573;
				}
				.zhong:hover{
					animation:second 2s 10;
				}
				.b:hover{
					border-radius:25px;
					box-shadow: 10px 10px 5px #888888;
				}
				.bb:hover{
					box-shadow: 10px 10px 5px #888888;
				}
				.c1:hover{
					border-radius:25px;
					box-shadow: 10px 10px 5px #888888;
					background-color:#e0e0e0;
				}
				.c11:hover{
					border-radius:25px;
					box-shadow: 10px 10px 5px #888888;
					background-color:#f8f8f8;
					animation:second 2s;
				}
				.c2:hover{
					border-radius:25px;
					box-shadow:10px 10px 5px #888888;
					background-color:#e0e0e0;
				}
				.c3:hover{
					border-radius:25px;
					box-shadow: 10px 10px 5px #888888;
					background-color:#e0e0e0;
				}
				.c4:hover{
					border-radius:25px;
					box-shadow: 10px 10px 5px #888888;
					background-color:#e0e0e0;
				}
				
		</style>
	</head>
	<body>
			<div class="zuo">
				<div class="zhong">
					<div class="ge front">个</div>
					<div class="ge left">人</div>
					<div class="ge back"></div>
					<div class="ge right">历</div>
				</div>
			</div>
			<div class="you">
				<div class="zhong">
					<div class="ge front">个</div>
					<div class="ge left">人</div>
					<div class="ge back"></div>
					<div class="ge right">历</div>
				</div>
			</div>
			
		<div class="a">
			<div class="b">
				<div class="bb">
					假装有照片
				</div>
				<ul class="bbb">
					<li>姓名：&nbsp陈晓</li>
					<li>性别：&nbsp男</li>
					<li>学校：<br>&nbsp&nbsp杭州电子科技大学<br>信息工程学院（本科）</li>
					<li>政治面貌：共青团员</li>
					<li>所在地：&nbsp杭州</li>
					<li>联系电话：<br>187-5885-1377</li>
					<li>联系邮箱：<br>815793632@qq.com</li>
				</ul>
			</div>
			<div class="c1">
				<div class="c11">个</div>
				<div class="c11">人</div>
				<div class="c11">简</div>
				<div class="c11">历</div>
				<div class="c12">求职意向：JAVA开发工程师</div>
			</div>
				<fieldset class="c2">
					<legend class="titles">教育背景</legend><hr>
					
					<p>2018.07-2018.09&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp杭州电子科技大学信息工程学院
						&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp通信工程（本科）
					<br>主修课程：数字电路，单片机原理与应用，模拟电子电路，通信原理，
					DSP芯片原理与应用，MATLAB,信号与系统 ，电路分析，C语言				
					</p>
				</fieldset>
				
				<fieldset class="c2">
					<legend class="titles">实习经历</legend><hr>
					
					<p>2017.07-2017.08&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp中国银行&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp实习生
					<br>&nbsp&nbsp&nbsp&nbsp负责对来银行的人做一些简单的引导，然后是简单了解银行的一些工作情况
					</p>
				</fieldset>
				<fieldset class="c3">
					<legend class="titles">校园经历</legend><hr>
					<p>
						2015.09-2018.05
						<br>1.参与的暑假社会实践获得优秀
						<br>2.参与校内社联三项比赛
						<br>3.完成了对单片机的简单处理
						<br>4.简单的完成了60s计时器的设计
					</p>
				</fieldset>
				<fieldset class="c4">
					<legend class="titles">技能</legend><hr>
					<p>
						熟练运用office、JAVA相关软件。简单运用ORCAD,以及MATLAB目前正在学习使用MySql、JDBC、
						HTML、CSS、JavaScript。
					</p>
				</fieldset>
				<fieldset class="c2">
					<legend class="titles">自我评价</legend><hr>
						<p>
							&nbsp&nbsp&nbsp&nbsp本人性格随和乐观，积极向上，爱好广泛，喜欢钻研，工作认真负责，
							拥有较强的组织能力和适应能力，并具有良好的身体素质。乐于沟通，易于融入集体，
							乐于助人，学习能力较好，注重理论与实践相结合，在工作中不断提高专业知识之余，
							同时也在不断地提高做人、做事的能力，争取将工作做得更好，争取做更好的自己！
						</p>
				</fieldset>
			</div>
		</div>
	</body>
</html>
