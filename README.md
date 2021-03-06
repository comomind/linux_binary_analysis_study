# 리눅스 바이너리 분석 스터디
[리눅스 바이너리 분석](http://www.acornpub.co.kr/book/linux-binary) 책을 읽고 관련 내용을 공유 하는 Repository 입니다.
원서 : [pdf](http://index-of.es/Miscellanous/Learning%20Linux%20Binary%20Analysis.pdf)

본 문서는 [마크다운](https://help.github.com/articles/basic-writing-and-formatting-syntax/) 문법을 이용하여 작성되며, 스터디에 참여하는 분은 자유롭게 수정이 가능합니다.

## TODO List

## Schedule
- [x] 3장, 리눅스 프로세스 추적 (p.91 ~ p.110) - 박정빈(8/16)
- [x] 3장, ptrace와 포렌식 분석 (p.111 ~ p.118) - 김주완(8/23)
- [x] 3장, ptrace를 활용한 코드 인젝션 (p.120 ~ p.132) - 전민지(8/30)
- [x] 4장, ELF 바이러스 기술 (p.133 ~ p.149) - 박재유(9/6)
         
         - http://www.bitlackeys.org/#retaliation
         - http://www.bitlackeys.org/projects/lpv.c //LPV 바이러스는 32비트 리눅스 시스템 기반으로 실비오 패딩 감염을 사용한다.
- [x] 4장, PT_NOTE에서 PT_LOAD로 변경하는 감염 방법 (p.150 ~ p.157) - 박정빈(9/18)

         - ssh passcode@pwnable.kr -p2222 (pw:guest) // got관련 문제 풀이 링크 입니다.(pwnable.kr의 passcode 문제)
         - https://github.com/elfmaster/skeksi_virus
         - https://github.com/elfmaster/saruman
         
- [x] 4장, 리모트 코드 인젝션 기술1 (p.157 ~ p.163) - 김주완(10/4)

         - http://www.hick.org/code/skape/papers/remote-library-injection.pdf
         - http://web.archive.org/web/20111222005751/http://vxheavens.com/lib/vrn00.html
         - https://grugq.github.io/docs/subversiveld.pdf
         - http://dbp-consulting.com/tutorials/debugging/linuxProgramStartup.html
         
- [x] 4장, 리모트 코드 인젝션 기술2 (p.157 ~ p.163) - 김주완(10/12)
- [x] 5장, 기존 ELF 바이너리 프로텍터 (P.163 ~ p.181) - 김주완, 박정빈 (11/19)

         - http://www.bitlackeys.org/projects/elfscure.c
- [ ] 5장, 기존 ELF 바이너리 프로텍터 (p.181 ~ ) - (11/29)

         - http://www.stratigery.com/userlandexec.html 
- [ ] 6장 부터는 미정
