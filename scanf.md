```c
%d	      int（整数）	                  scanf("%d", &x);
%f	      float（单精度浮点数）	        scanf("%f", &y);
%lf      	double（双精度浮点数）	        scanf("%lf", &z);
%c	      char（单个字符）	              scanf(" %c", &ch);（注意前面有空格）
%s	      char 数组（字符串）	          scanf("%s", name);（不能输入带空格的字符串）
%[^\n]	  读取整行字符串（包含空格）	    scanf("%[^\n]", str);
%u	      unsigned int（无符号整数）	    scanf("%u", &n);
%x /%X	  读取十六进制整数	              scanf("%x", &hex);
%o	      读取八进制整数	                scanf("%o", &oct);
%p	      读取指针地址	                  scanf("%p", &ptr);
%e / %E	  指数形式的浮点数	              scanf("%e", &num);
%%	      读取 % 符号	                  scanf("%%");
