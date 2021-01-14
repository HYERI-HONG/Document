How to create SSH Key
==

1. Git bash에서 SSH key 생성

```bash
ssh-keygen
```

2. cmd에서 생성된 SSH key 확인

```bash
cd .ssh      
type id_rsa.pub
```

3. 명령어 입력시 나오는 SSH Key값을 Github에 세팅
   - Github 로그인 > Settings > SSH and GPG Keys > New SSH Key 등록
