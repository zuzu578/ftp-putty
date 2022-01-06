# ftp-putty

# putty 접근

1) aws 일경우

- key file 을 putty gen 을 이용하여 pem 파일을 ppk로 변환한다
- 그런다음 putty 접속정보와 함께 auth 에서 ppk 파일을 불러와서 접근한다.

# ftp pem 파일로 연결방법

1) 파일질라에서 설정에서 .pem 파일을 추가한다
2) 파일 > 사이트관리자에서  SFTP 프로토콜 선택후 연결한다. 
