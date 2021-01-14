# How to use RealGrid

<br/>
<br/>

## RealGrid Object
---
<br/>

> GridView
- 그리드를 화면에 그려주는 객체

```vue
<script>
import { GridView} from 'realgrid'
let gridView = GridView



```

> Data Provider

- 그리드 영역에 보여질 데이터를관리하는 객체
- 데이터 참조시 사용하는 값 : DataRow
- 데이터셋에 담을 수 있는 형식
  - Json
  - XML
  - CSV
  - Javascript Array
  
> ItemModel

- 그리드 영역의 데이터 순서 정보 관리(정렬, 필터, 페이징 처리 가능)
- 순서 참조시 사용하는 값 : ItemIndex

<br/>
<br/>
<br/>

## RealGrid Install
---

<br>

> 라이센스 발급 및 설치

1. 사용자 등록 or 로그인(service.realgrid.com) 
   1. ID : hrhong PW : 1111
2. 프로젝트 추가
3. 개발용 라이선스 발급
4. 라이선스 다운로드
5. 압축풀어 realgrid.lic.js 파일 editor에서 열어 라이선스키 확인
   ```javascript
   var realGrid2Lic = 'upVcPE+wPOmtLjqyBIh9RkM/nBOseBrflwxYpzGZyYm9cY8amGDkiHqyYT2U1Yh3Dufv8SUhNy6KQlABKJ+p1Q==';
   ```
6. 해당 코드를 index.html에 추가
