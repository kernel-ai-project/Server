name: "🧹 Refactor"
description: "코드 리팩토링 작업"
labels: ["refactor"]
body:
  - type: textarea
    attributes:
      label: 📄 리팩토링 대상
      description: 어떤 부분을 리팩토링할지 작성해 주세요.
      placeholder: 예) Service 계층 비즈니스 로직 분리, 불필요한 의존성 제거 등
    validations:
      required: true
  - type: textarea
    attributes:
      label: 🧩 리팩토링 상세 내용
      description: 구체적으로 어떤 개선을 진행할지 작성해 주세요.
      placeholder: 클래스/메서드 단위로 세분화해서 작성해 주세요.
    validations:
      required: true
  - type: textarea
    attributes:
      label: ⚙️ 기대 효과
      description: 리팩토링 후 기대되는 효과를 적어주세요.
      placeholder: 예) 유지보수성 향상, 중복 코드 제거, 성능 개선 등
  - type: textarea
    attributes:
      label: 🙋🏻 참고 자료
      description: 관련 문서나 참고한 자료가 있다면 작성해 주세요.
