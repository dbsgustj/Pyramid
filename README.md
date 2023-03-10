# Pyramid
		Scanner sc = new Scanner(System.in);
		System.out.println("몇단의 피라미드를 만들까요?");
		int i; //i방 생성
		int j; //j방 생성
		int k; //k방 생성
		int n = sc.nextInt(); //n방 생성/입력한걸 받아둔다
		
		for(i=0;i<n;i++) { //i방은 n에 사용자가 입력한 수의 미만값까지 커진다
			for(j=1;j<n-i;j++) { //j방은 n-i수의 미만값까지 커진다.
				System.out.print(" "); //한 번 돌때마다 j만큼 공백을 찍는다 
			}
			for(k=0;k<i*2+1;k++) { //k방은 i*2+1수의 미만값까지 커진다
				System.out.print("*"); //한 번 돌때마다 k만큼 *을 찍는다
			}
			System.out.println(); //한 번 돌때마다 밑칸으로 넘어간다.
		}
		
	}

}
![스크린샷(1)](https://user-images.githubusercontent.com/126844596/224194394-db97bb51-77df-41d4-b8a2-47170b5076b2.png)
