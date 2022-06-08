# clone의 권한 거부 오류

github에서 clone을 하는 과정에서 git bash에서 권한이 없어 접근이 불가능하다는 오류메세지 출력

cmd에서 git config --system --unset credential.helper 입력후 이메일과 비밀번호 재설정후 다시 시도

error: could not lock config file C:/Program Files/Git/etc/gitconfig: Permission denied
라는 오류메세지 출력됨.



### 오류원인
cmd를 관리자 권한으로 실행하지 않았음
