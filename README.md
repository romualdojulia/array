# array
Exercícios sobre array

/*Exercício 01*/

public class Exercicio1 {

	public static void main(String[] args) {
		
		Integer[] array = new Integer[9];
		
		for(int i=0; i<=8; i++) {
			array[i] = i;
			System.out.println(array[i]);
		}
		
		System.out.println("\nvalores multiplicados por 3\n");
		for(int i=0; i<=8; i++) {
			array[i] = i;
			System.out.println(array[i]*3);
		}
	}
}

/*Exercício 02*/

public class Exercicio2 {

	public static void main(String[] args) {
		
		Integer[] array = new Integer[10];
		
		for(int i=9; i>0; i--) {
			array[i] = i;
			System.out.println(array[i]);
		}
	}
}

/*Exercício 03*/

public class Exercicio3 {

	public static void main(String[] args) {

		Integer[][] arraybid = new Integer[100][100];
		
		for(int i=0; i<100;i++) {
			for(int j=0;j<100;j++) {
				arraybid[i][j] = i-j;
				System.out.println(arraybid[i][j]);
			}
		}
		
		for(int i=0; i<100;i++) {
			for(int j=0;j<100;j++) {
				arraybid[i][j] *=7; 
				System.out.println(arraybid[i][j]);
			}
		}
	}
}

/*Exercício 04*/

public class Exercicio4 {

	public static void main(String[] args) {

		Integer[][] a = new Integer[50][100];
		
		for(int i=49;i>0;i--) {
			for(int j=99; j>0;j--) {
				a[i][j] = i+j;
				System.out.println(a[i][j]);
			}
		}
	}
}
