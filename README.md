# Pyramid
		Scanner sc = new Scanner(System.in);
		System.out.println("몇단의 피라미드를 만들까요?");
		int i;
		int j;
		int k;
		int n = sc.nextInt();
		
		for(i=0;i<n;i++) {
			for(j=1;j<n-i;j++) {
				System.out.print(" ");
			}
			for(k=0;k<i*2+1;k++) {
				System.out.print("*");
			}
			System.out.println();
		}
		
	}

}
