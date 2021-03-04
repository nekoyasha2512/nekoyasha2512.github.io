
# CCE程式設計 109下
## 第一周 2021/02/22
### 進階題：分式化簡
```C
#include <stdio.h>
int main()
{

	int a, b, c, x, y;
	scanf("%d%d",&a ,&b);
	x=a; y=b;
	while( b!=0 )
	{
		c=b;
		b=a%b;
		a=c;
	}
	x/=a;
	y/=a;
	printf("%d %d\n", x, y);

}
```
