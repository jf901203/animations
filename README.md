
##当您在 @keyframes 中创建动画时，请把它捆绑到某个选择器，否则不会产生动画效果。

		#demo{
				width: 200px;
				height:200px;
				background:blue;
				animation:move .5s;
				margin:0px auto;
			}

		@keyframes move{
		  
		   0%{
		   	 transform:scale(1);
		   }
		   35%{
		   	 transform:scale(.8);
		   }
		   70%{
		   	 transform:scale(1.1);
		   }
		   100%{
		   	 transform:scale(1);
		   }
			
      }