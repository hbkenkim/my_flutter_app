# My Flutter Project


## Flutter Sources

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


## 라이브러리 폴더 구조

- main.dart                # 앱의 시작점
- app.dart                 # MaterialApp 설정 및 전역 테마 정의 (optional)

- screens/                 # 각 메뉴나 전체 화면 (Page 단위)
    - home(예시)/
        - home_screen.dart # 네비게이션 바가 있는 메인 뼈대
        - widgets/         # 홈 화면에서만 쓰이는 작은 부품들
    - login(예시)/
        - login_screen.dart

- widgets/                 # 앱 전체에서 공통으로 쓰이는 커스텀 위젯
    - custom_button.dart   # 공통 버튼

- models/                  # 데이터 구조 (Data Class / JSON 모델)
    - user_model.dart

- providers/ (또는 bloc/)   # 상태 관리 파일 (데이터 흐름 제어)
    - user_provider.dart

- services/                # API 통신, Firebase, 로컬 DB 연동
    - api_service.dart

- utils/                   # 공통 함수, 상수, 색상  
    - constants.dart 
    - colors.dart