# 자료구조

## 배열리스트와 연력리스트 비교

구분 | 구현 방식 | 순차적 저장을 구한형 방식 | 자료 접근 속도 | 구현 복잡도 | 기타 제약 사항
--- | --- | --- | --- | --- | ---
배열 리스트|배열|물리적 저장 순서가 순차적|빠름 O(1)|낮음|최대 정장 개수 필요
연결 리스트|포인터|논리적 저장 순서가 순차적|느림 O(n)|높음|-

- 저장하는 자료의 크기가 크다면 배열 리스트는 자료를 추가할 때에 노드 이동 때문에 더 많은 시간이 소요
- 자료의 추가와 삭제가 빈번히 발생할 때에는 배열 리스트보다 연결 리스트로 구현