# java-
第一个在Github里上传的java冒泡排序测试用例
import static org.junit.jupiter.api.Assertions.*;

import org.junit.jupiter.api.Test;


class hzw {

	@Test
	void test() {
	//	fail("Not yet implemented");
	  	int a[]= {10,1,8,12,3 };
		for(int i=0;i<a.length;i++)
			 System.out.print(a[i]+"\t");
			int i = 0;
			for(int j=0;i<a.length-1;i++) 
			{
				for(int j1=0;j1<a.length -i-1;j1++)
				{
					if(a[j1]<a[j1+1])
					{
						int temp=a[j1];
						a[j1]=a[j1+1];
						a[j1]=a[j1+1];
						a[j1+1]=temp;
						
					}
				}
			}
		for(int i1=0;i1<a.length ;i1++)
			System.out.print(a[i1]+"\t");
		System.out.println();
	
		
	}

}
