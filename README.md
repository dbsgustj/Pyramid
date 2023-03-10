# Pyramid
# 설명
별모양을 이용한 피라미드 모양 만들기!

먼저 피라미드모양을 잡기위해선 공백을 찍어야하는데 공식은 (원하는 층)-(현재 층)이다.

그리고 피라미드 모양을 만들기위해 별을 찍어야하는데 별은 (현재 층) - 1 X 2 +1 이다. 여기선 곱하기를 먼저 하지 않는다.

그리고 다음줄로 이동시킨다. 만약 이동시키지 않는다면 공백 별 공백 별 순으로 옆으로만 뛰어져서 찍히게 될것이다

# 코드
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
			System.out.println(); //한 번 돌때마다 다음줄로 넘어간다.
		}
		
	}

}
![스크린샷(1)](https://user-images.githubusercontent.com/126844596/224194394-db97bb51-77df-41d4-b8a2-47170b5076b2.png)
