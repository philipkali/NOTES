~~~~
O(n)  
void foo(int[]array){  
	int sum = 0;  
	int product = 1;  
	for (int i = 0; i < array.length; i++){  
		sum += array[i];  
	}  
	for (int i = 0; i < array.length; i++){  
		product *= array[i];  
	}  
	System.out.println(sum + ", " + product);  
}  
~~~~

~~~~
---------

void reverse(int[] array){
	for (int i = 0; i < array.length / 2; i++) {
		int other = array.length - i -1;
		int temp = array[i];
		array[i] = array[other];
		array[other] = temp;
	}
}



~~~~
