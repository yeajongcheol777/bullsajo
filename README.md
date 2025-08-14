# 정렬 알고리즘 구현 프로젝트

이 프로젝트는 다양한 정렬 알고리즘을 Python으로 구현한 학습용 프로젝트입니다.

## 파일 구조

```
bullsajo-1/
├── main.py          # 정렬 알고리즘 구현 및 실행
├── data.txt         # 정렬할 데이터 파일
└── README.md        # 프로젝트 설명서
```

## 구현된 정렬 알고리즘

### ✅ 버블 정렬 (Bubble Sort)
- **시간 복잡도**: O(n²)
- **공간 복잡도**: O(1)
- **특징**: 인접한 두 요소를 비교하여 정렬하는 안정 정렬
- **최적화**: 조기 종료 기능 포함

### 🚧 구현 예정
- 선택 정렬 (Selection Sort)
- 삽입 정렬 (Insertion Sort)
- 병합 정렬 (Merge Sort)
- 퀵 정렬 (Quick Sort)
- 힙 정렬 (Heap Sort)

## 사용 방법

### 1. 프로젝트 클론
```bash
git clone https://github.com/yeajongcheol777/bullsajo.git
cd bullsajo-1
```

### 2. 데이터 파일 준비
`data.txt` 파일에 정렬할 숫자들을 쉼표로 구분하여 입력:
```
549, 288, 82, 371, 822, 244, 126, 30, ...
```

### 3. 프로그램 실행
```bash
python main.py
```

## 실행 결과 예시

```
원본 데이터: [549, 288, 82, 371, 822, ...]

[버블 정렬 결과]
[4, 5, 7, 8, 10, 10, 13, 16, 18, 18, ...]

[선택 정렬 결과]
구현 예정

[삽입 정렬 결과]
구현 예정
...
```

## 기능

- **모듈화된 설계**: 각 정렬 알고리즘이 독립적인 함수로 구현
- **원본 데이터 보호**: 정렬 시 원본 배열을 변경하지 않음
- **다양한 알고리즘 지원**: 여러 정렬 방식을 한 번에 테스트 가능
- **대용량 데이터 처리**: 효율적인 메모리 사용

## 개발 환경

- **언어**: Python 3.x
- **의존성**: 표준 라이브러리만 사용
- **테스트 데이터**: 1000개 이상의 랜덤 정수

## 기여하기

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다.

## 작성자

- GitHub: [@yeajongcheol777](https://github.com/yeajongcheol777)