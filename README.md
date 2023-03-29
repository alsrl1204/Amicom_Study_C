# Amicom C 스터디 연습장

- 아미콤 C 스터디 전용 레포지토리입니다.
- 매 주차마다 학습 내용과 실습 내용을 README 파일과 각자의 C 파일에 자유롭게 작성합니다.
- 정해진 작성 형식은 없습니다.

## 1주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 2주차 배운 내용
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
1.
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main() {
	int n;

	printf("1<=n<=100\n");
	printf("Enter a number: ");
	scanf("%d", &n);

	if ((n % 2 != 0 && n % 3 == 0) || (n % 2 == 0 && n % 5 == 0)) {
		printf("true");
	}
	else {
		printf("false");
	}

	return 0;
}

2.
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main() {
	int a;							// 문자형 변수 a 지정

	printf("Enter a number: ");		// 숫자 입력
	scanf("%d", &a);				// 입력받은 숫자를 a에 저장

	if (a % 2 != 0 && a < 5) {
		printf("A");
	}
	else if (a % 2 != 0 && a >= 5) {
		printf("B");
	}
	else if (a % 2 == 0) {
		printf("C");
	}

	return 0;
}

3.
int main() {
    int i;
    int j;

    for (i = 1; i <= 6; i++) {
        if (i % 2 != 0) {
            for (j = 1; j <= i; j++) {
                printf("*");
            }
        }
        else {
            printf("$");
        }
        printf("\n");
    }

    return 0;
}


## 3주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 4주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 5주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 6주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 7주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 8주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 9주차 배운 내용
- 이곳에 작성하시면 됩니다.

## 10주차 배운 내용
- 이곳에 작성하시면 됩니다.
